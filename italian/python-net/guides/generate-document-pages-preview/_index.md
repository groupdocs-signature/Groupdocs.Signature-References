---
title: "Genera l'anteprima delle pagine del documento"
linkTitle: "Generate document pages preview"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Questo argomento spiega come ottenere l'anteprima delle pagine del documento come immagini con varie opzioni tramite GroupDocs.Signature per Python via .NET."
type: docs
url: /it/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
Ecco i passaggi per generare l'anteprima del documento con GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

Il flusso restituito dalla funzione create viene chiuso automaticamente non appena l'immagine della pagina è scritta: un file viene chiuso e un `io.BytesIO` contiene già l'immagine completa. Se è necessario elaborare ogni immagine terminata o liberare le risorse manualmente, passa una funzione di rilascio come argomento aggiuntivo (vedi [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/)).

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

GroupDocs.Signature chiama la funzione create una volta per ogni pagina e scrive l'immagine della pagina nel flusso restituito: un oggetto file scrivibile, un `io.BytesIO` o un flusso .NET. L'argomento `page_data` è un oggetto [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/) con il `page_number`, il `file_name` del documento e il `preview_format`.

I numeri di pagina sono basati su 0: `page_data.page_number` è `0` per la prima pagina del documento.

```python
def create_page_stream(page_data):
    # Basato su 0: preview_page_0.png è la prima pagina
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

Quando visualizzi un archivio, la funzione viene chiamata per le pagine di ogni documento al suo interno. I numeri di pagina ricominciano da `0` per ciascun documento, quindi utilizza anche `page_data.file_name` quando nomini le immagini.

## ReleasePageStream delegate implementation

La funzione di rilascio riceve lo stesso `page_data` e lo stesso oggetto restituito dalla funzione create. Al momento della sua chiamata, l'immagine è completa.

```python
def release_page_stream(page_data, page_stream):
    # page_stream è l'oggetto restituito da create_page_stream
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs "generate_document_preview" >}}
{{< tab \"Python\" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # I numeri di pagina sono basati su 0: preview_page_0.png è la prima pagina
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # Crea l'oggetto delle opzioni di anteprima: un'immagine PNG per pagina
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # Genera anteprima
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) per scaricarlo.

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

Questo esempio legge il documento da uno stream e mantiene le immagini delle pagine in memoria: la funzione create restituisce un `io.BytesIO`, e la funzione release lo riceve riempito con l'immagine completa.

{{< tabs \"generate_document_preview_from_stream\" >}}
{{< tab \"Python\" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Mantieni ogni immagine di pagina in memoria invece di scrivere un file
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # page_stream è il BytesIO restituito sopra, che contiene già l'intera immagine
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # Crea l'oggetto delle opzioni di anteprima con entrambe le funzioni
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # Genera anteprima
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) per scaricarlo.

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

Imposta `page_numbers` per visualizzare in anteprima solo alcune pagine. I numeri sono basati su 0, quindi `[1]` seleziona la seconda pagina.

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
        # I numeri di pagina sono basati su 0: [1] è la seconda pagina
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) per scaricarlo.

{{< /tab >}}
{{< tab \"preview_page_1.png\" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

La risoluzione predefinita è 96 DPI. Passa la risoluzione come terzo argomento di [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/), oppure imposta la proprietà `resolution`.

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
        # Crea l'oggetto delle opzioni di anteprima: 150 DPI invece dei 96 predefiniti
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # Genera anteprima
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) per scaricarlo.

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

Puoi facilmente eseguire il codice sopra e vedere la funzionalità in azione nei nostri esempi su GitHub:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Oltre alla libreria Python completa, forniamo semplici ma potenti app online gratuite.

Per firmare PDF, Word, Excel, PowerPoint e altri documenti puoi utilizzare le app online della **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
