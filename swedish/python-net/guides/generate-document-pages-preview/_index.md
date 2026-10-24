---
title: "Generera förhandsgranskning av dokumentsidor"
linkTitle: "Generate document pages preview"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Detta avsnitt förklarar hur du får en förhandsgranskning av dokumentsidor som bilder med olika alternativ med GroupDocs.Signature för Python via .NET."
type: docs
url: /sv/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
Här är stegen för att generera dokumentförhandsgranskning med GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

Strömmen som returneras av create‑funktionen stängs automatiskt så snart sidbilden har skrivits: en fil stängs och ett `io.BytesIO` redan innehåller den kompletta bilden. Om du behöver bearbeta varje färdig bild eller själv rensa resurser, skicka en release‑funktion som ett extra argument (se [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/)).

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

GroupDocs.Signature anropar create‑funktionen en gång för varje sida och skriver sidbilden till den ström den returnerar: ett skrivbart filobjekt, ett `io.BytesIO` eller en .NET‑ström. Argumentet `page_data` är ett [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/)‑objekt med `page_number`, `file_name` för dokumentet och `preview_format`.

Sidnumren är nollbaserade: `page_data.page_number` är `0` för den första sidan i dokumentet.

```python
def create_page_stream(page_data):
    # Nollbaserad: preview_page_0.png är den första sidan
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

När du förhandsgranskar ett arkiv anropas funktionen för sidorna i varje dokument i det. Sidnumren börjar återigen på `0` för varje dokument, så använd även `page_data.file_name` när du namnger bilderna.

## ReleasePageStream delegate implementation

Release‑funktionen får samma `page_data` och samma objekt som create‑funktionen returnerade. När den anropas är bilden färdig.

```python
def release_page_stream(page_data, page_stream):
    # page_stream är det objekt som create_page_stream returnerade
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs "generate_document_preview" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Sidnummer är 0-baserade: preview_page_0.png är den första sidan
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # Skapa förhandsgranskningsalternativobjekt: en PNG-bild per sida
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # Generera förhandsgranskning
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"generate-document-preview-outputs.zip\" >}}
```text
preview_page_0.png (75 KB)
preview_page_1.png (64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview/generate-document-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Generate document preview from stream with custom stream releasing delegate

Detta exempel läser dokumentet från en ström och behåller sidbilderna i minnet: create-funktionen returnerar en `io.BytesIO`, och release-funktionen tar emot den fylld med den kompletta bilden.

{{< tabs \"generate_document_preview_from_stream\" >}}
{{< tab \"Python\" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Behåll varje sidbild i minnet istället för att skriva en fil
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # page_stream är den BytesIO som returnerades ovan, och som redan innehåller hela bilden
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # Skapa förhandsgranskningsalternativobjekt med båda funktionerna
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # Generera förhandsgranskning
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"generate-document-preview-from-stream.txt\" >}}
```text
Page 0: 276044 bytes of JPEG
Page 1: 224194 bytes of JPEG
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_from_stream/generate-document-preview-from-stream.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate preview of particular pages

Ställ in `page_numbers` för att förhandsgranska endast vissa sidor. Nummerna är 0-baserade, så `[1]` väljer den andra sidan.

{{< tabs \"generate_document_preview_of_selected_pages\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}.png", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_of_selected_pages():
    with Signature("sample.pdf") as signature:
        preview_options = PreviewOptions(create_page_stream, release_page_stream)
        # Sidnummer är 0-baserade: [1] är den andra sidan
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"preview_page_1.png\" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

Standardupplösningen är 96 DPI. Skicka upplösningen som det tredje argumentet till [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/), eller sätt `resolution`-egenskapen.

{{< tabs \"generate_document_preview_with_resolution\" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    return open(f"preview_page_{page_data.page_number}_150dpi.jpg", "wb")

def release_page_stream(page_data, page_stream):
    print(f"Image file {page_stream.name} is ready for preview")

def generate_document_preview_with_resolution():
    with Signature("sample.pdf") as signature:
        resolution = 150
        # Skapa förhandsgranskningsalternativobjekt: 150 DPI istället för standarden 96
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # Generera förhandsgranskning
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) för att ladda ner den.

{{< /tab >}}
{{< tab \"generate-document-preview-with-resolution-outputs.zip\" >}}
```text
preview_page_0_150dpi.jpg (495 KB)
preview_page_1_150dpi.jpg (425 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_with_resolution/generate-document-preview-with-resolution-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

Du kan enkelt köra koden ovan och se funktionen i praktiken i våra GitHub-exempel:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Tillsammans med det fullständiga Python-biblioteket erbjuder vi enkla men kraftfulla gratis online‑appar.

För att signera PDF, Word, Excel, PowerPoint och andra dokument kan du använda de online‑apparna från **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
