---
title: "metode generate_preview"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Membuat pratinjau halaman dokumen."
type: docs
url: /id/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

Membuat pratinjau halaman dokumen.

Pelajari lebih lanjut tentang cara menghasilkan pratinjau untuk halaman dokumen:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Opsi pratinjau. |

### Contoh

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
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```

### Lihat Juga
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
