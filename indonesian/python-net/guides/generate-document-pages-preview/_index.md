---
title: "Buat pratinjau halaman dokumen"
linkTitle: "Generate document pages preview"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Topik ini menjelaskan cara mendapatkan pratinjau halaman dokumen sebagai gambar dengan berbagai opsi oleh GroupDocs.Signature untuk Python via .NET."
type: docs
url: /id/python-net/guides/generate-document-pages-preview/
is_root: false
weight: 130
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) class to specify different options to manage document pages preview generation process. The feature also supports archives previewing.
  
Berikut langkah-langkah untuk menghasilkan pratinjau dokumen dengan GroupDocs.Signature:

* Create new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass source document path or stream as a constructor parameter.
* Instantiate the [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) object with:
* a function that creates a stream for each page image (see [CreateDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createdocpagestream/));
* image preview format - PNG / JPEG / BMP,
* page numbers to process;
* custom resolution of preview images (if needed).

Stream yang dikembalikan oleh fungsi create ditutup secara otomatis segera setelah gambar halaman ditulis: sebuah file ditutup, dan `io.BytesIO` sudah memuat gambar lengkap. Jika Anda perlu memproses setiap gambar yang selesai atau membersihkan sumber daya sendiri, berikan fungsi release sebagai argumen tambahan (lihat [ReleaseDocPageStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasedocpagestream/)).

* Call `generate_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class instance and pass [PreviewOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewoptions/) to it.

## CreatePageStream delegate implementation

GroupDocs.Signature memanggil fungsi create sekali untuk setiap halaman dan menulis gambar halaman ke dalam stream yang dikembalikannya: sebuah objek file yang dapat ditulis, `io.BytesIO`, atau stream .NET. Argumen `page_data` adalah objek [PreviewPageData](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewpagedata/) dengan `page_number`, `file_name` dokumen, dan `preview_format`.

Nomor halaman dimulai dari 0: `page_data.page_number` adalah `0` untuk halaman pertama dokumen.

```python
def create_page_stream(page_data):
    # Berbasis 0: preview_page_0.png adalah halaman pertama
    return open(f"preview_page_{page_data.page_number}.png", "wb")
```

Ketika Anda meninjau arsip, fungsi dipanggil untuk halaman setiap dokumen di dalamnya. Nomor halaman dimulai kembali dari `0` untuk setiap dokumen, jadi gunakan juga `page_data.file_name` saat memberi nama pada gambar.

## ReleasePageStream delegate implementation

Fungsi release menerima `page_data` yang sama dan objek yang sama yang dikembalikan oleh fungsi create. Pada saat dipanggil, gambar sudah lengkap.

```python
def release_page_stream(page_data, page_stream):
    # page_stream adalah objek yang dikembalikan oleh create_page_stream
    print(f"Image file {page_stream.name} is ready for preview")
```

## Generate document preview from file on local disk

{{< tabs \"generate_document_preview\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Nomor halaman berbasis 0: preview_page_0.png adalah halaman pertama
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

def generate_document_preview():
    with Signature("sample.pdf") as signature:
        # Buat objek opsi pratinjau: satu gambar PNG per halaman
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        # Hasilkan pratinjau
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) untuk mengunduhnya.

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

Contoh ini membaca dokumen dari aliran dan menyimpan gambar halaman di memori: fungsi create mengembalikan sebuah `io.BytesIO`, dan fungsi release menerima objek yang telah terisi dengan gambar lengkap.

{{< tabs "generate_document_preview_from_stream" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    # Simpan setiap gambar halaman di memori alih-alih menulis ke file
    return io.BytesIO()

def release_page_stream(page_data, page_stream):
    # page_stream adalah BytesIO yang dikembalikan di atas, yang sudah berisi seluruh gambar
    image = page_stream.getvalue()
    print(f"Page {page_data.page_number}: {len(image)} bytes of JPEG")

def generate_document_preview_from_stream():
    with open("sample.pdf", "rb") as stream:
        with Signature(stream) as signature:
            # Buat objek opsi pratinjau dengan kedua fungsi
            preview_options = PreviewOptions(create_page_stream, release_page_stream)
            preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
            # Hasilkan pratinjau
            signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) untuk mengunduhnya.

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

Atur `page_numbers` untuk menampilkan pratinjau hanya beberapa halaman. Angka-angka tersebut berbasis 0, jadi `[1]` memilih halaman kedua.

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
        # Nomor halaman berbasis 0: [1] adalah halaman kedua
        preview_options.page_numbers = [1]
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_of_selected_pages()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "preview_page_1.png" >}}
```text
Binary file (PNG, 64 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-document-pages-preview/generate_document_preview_of_selected_pages/preview_page_1.png)
{{< /tab >}}
{{< /tabs >}}

## Creating a document preview with custom Resolution

Resolusi default adalah 96 DPI. Berikan resolusi sebagai argumen ketiga dari [`PreviewOptions`](/signature/python-net/groupdocs.signature.options/previewoptions/), atau atur properti `resolution`.

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
        # Buat objek opsi pratinjau: 150 DPI alih-alih 96 default
        preview_options = PreviewOptions(create_page_stream, release_page_stream, resolution)
        preview_options.preview_format = PreviewOptions.PreviewFormats.JPEG
        # Hasilkan pratinjau
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview_with_resolution()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/generate-document-pages-preview/sample.pdf) untuk mengunduhnya.

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

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur ini beraksi dalam contoh GitHub kami:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Bersamaan dengan pustaka Python yang lengkap, kami menyediakan aplikasi daring gratis yang sederhana namun kuat.

Untuk menandatangani PDF, Word, Excel, PowerPoint, dan dokumen lainnya, Anda dapat menggunakan aplikasi online dari **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
