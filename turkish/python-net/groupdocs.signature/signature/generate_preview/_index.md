---
title: "generate_preview yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belge sayfalarının önizlemesini oluşturur."
type: docs
url: /tr/python-net/groupdocs.signature/signature/generate_preview/
is_root: false
weight: 1100
---


## generate_preview {#preview_options}

Belge sayfalarının önizlemesini oluşturur.

Belge sayfaları için önizlemeler oluşturma hakkında daha fazla bilgi edinin:
- How to generate document pages preview using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Generate+document+pages+preview)

```python
def generate_preview(self, preview_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Önizleme seçenekleri. |

### Örnek

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
        preview_options = PreviewOptions(create_page_stream)
        preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
        signature.generate_preview(preview_options)

if __name__ == "__main__":
    generate_document_preview()
```

### Ayrıca Bakınız
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
