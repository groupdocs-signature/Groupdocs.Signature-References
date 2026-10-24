---
title: "Belge sayfalarının önizlemesini oluştur"
linkTitle: "Generate document pages preview"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bu konu, .NET üzerinden Python için GroupDocs.Signature kullanarak belge sayfalarının önizlemesini çeşitli seçeneklerle görüntü olarak nasıl alacağınızı açıklar."
type: docs
url: /tr/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
GroupDocs.Signature ile belge önizlemesi oluşturmak için adımlar şunlardır:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

create işlevi tarafından döndürülen akış, sayfa görüntüsü yazıldıktan hemen sonra otomatik olarak kapatılır: bir dosya kapanır ve `io.BytesIO` zaten tam görüntüyü tutar. Her bitmiş görüntüyü işlemek veya kaynakları kendiniz temizlemek isterseniz, ek bir argüman olarak bir release işlevi geçirin (bkz. [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/)).

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

GroupDocs.Signature, her sayfa için create işlevini bir kez çağırır ve sayfa görüntüsünü döndürdüğü akışa yazar: yazılabilir bir dosya nesnesi, bir `io.BytesIO` veya bir .NET akışı. `page_data` argümanı, `page_number`, belgenin `file_name` ve `preview_format` içeren bir [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/) nesnesidir.

Sayfa numaraları 0 tabanlıdır: `page_data.page_number` belgenin ilk sayfası için `0` dır.

```python
def create_page_stream(page_data):
    # 0 tabanlı: preview_page_0.png ilk sayfadır
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

Bir arşivi önizlediğinizde, işlev içinde bulunan her belgenin sayfaları için çağrılır. Sayfa numaraları her belge için tekrar `0`'dan başlar, bu yüzden görüntüleri adlandırırken `page_data.file_name` değerini de kullanın.

## ReleasePageStream delegate implementation

Release işlevi aynı `page_data` ve create işlevinin döndürdüğü aynı nesneyi alır. Çağrıldığı anda görüntü tamamlanmıştır.

```python
def release_page_stream(page_data, page_stream):
    # page_stream, create_page_stream tarafından döndürülen nesnedir
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs \"generate_document_preview\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Sayfa numaraları 0 tabanlıdır: preview_page_0.png ilk sayfadır
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # Önizleme seçenekleri nesnesi oluşturun: sayfa başına bir PNG resmi
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # Önizleme oluştur
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "generate-document-preview-outputs.zip" >}}
```text
preview_page_0.png (75 KB)
preview_page_1.png (64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview/generate-document-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Generate document preview from stream with custom stream releasing delegate

Bu örnek belgeyi bir akıştan okur ve sayfa görüntülerini bellekte tutar: create işlevi bir `io.BytesIO` döndürür ve release işlevi tamamlanmış görüntüyle doldurulmuş olarak alır.

{{< tabs "generate_document_preview_from_stream" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Her sayfa görüntüsünü dosyaya yazmak yerine bellekte tutun
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # page_stream, yukarıda döndürülen BytesIO'dur ve zaten tüm görüntüyü içerir
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # Her iki işlevle birlikte önizleme seçenekleri nesnesi oluşturun
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # Önizleme oluştur
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "generate-document-preview-from-stream.txt" >}}
```text
Page 0: 276044 bytes of JPEG
Page 1: 224194 bytes of JPEG
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_from_stream/generate-document-preview-from-stream.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate preview of particular pages

`page_numbers`'ı yalnızca bazı sayfaları önizlemek için ayarlayın. Sayılar 0 tabanlıdır, bu yüzden `[1]` ikinci sayfayı seçer.

{{< tabs "generate_document_preview_of_selected_pages" >}}
{{< tab "Python" >}}
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
        # Sayfa numaraları 0 tabanlıdır: [1] ikinci sayfadır
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "preview_page_1.png" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

Varsayılan çözünürlük 96 DPI'dir. Çözünürlüğü [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/) üçüncü argüman olarak geçirin veya `resolution` özelliğini ayarlayın.

{{< tabs "generate_document_preview_with_resolution" >}}
{{< tab "Python" >}}
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
        # Önizleme seçenekleri nesnesi oluşturun: varsayılan 96 yerine 150 DPI
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # Önizleme oluştur
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "generate-document-preview-with-resolution-outputs.zip" >}}
```text
preview_page_0_150dpi.jpg (495 KB)
preview_page_1_150dpi.jpg (425 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_with_resolution/generate-document-preview-with-resolution-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

Yukarıdaki kodu kolayca çalıştırabilir ve GitHub örneklerimizde özelliğin nasıl çalıştığını görebilirsiniz:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Tam özellikli Python kütüphanesiyle birlikte, basit ama güçlü ücretsiz çevrimiçi uygulamalar da sunuyoruz.

PDF, Word, Excel, PowerPoint ve diğer belgeleri imzalamak için **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** adresindeki çevrimiçi uygulamaları kullanabilirsiniz.
