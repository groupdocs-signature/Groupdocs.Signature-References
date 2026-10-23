---
title: "kelas PreviewOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi pratinjau dokumen."
type: docs
url: /id/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Mewakili opsi pratinjau dokumen.

Tipe PreviewOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | Tinggi gambar pratinjau. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | Bendera yang menunjukkan apakah tanda tangan disembunyikan dari gambar pratinjau halaman. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | Nomor halaman gambar pratinjau. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | Format gambar pratinjau. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | Resolusi gambar pratinjau dalam DPI (dot per inci). Resolusi default adalah 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | Lebar gambar pratinjau. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

with Signature("sample.pdf") as signature:
    preview_options = PreviewOptions(create_page_stream)
    preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
    signature.generate_preview(preview_options)
```

### Guides
Panduan tugas yang menggunakan `PreviewOptions`:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
