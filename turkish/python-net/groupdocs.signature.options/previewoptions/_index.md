---
title: "PreviewOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belge önizleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Belge önizleme seçeneklerini temsil eder.

PreviewOptions türü aşağıdaki üyeleri ortaya çıkar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | Ön izleme görüntülerinin yüksekliği. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | İmzaların sayfa ön izleme görüntülerinden gizlenip gizlenmediğini belirten bayrak. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | Ön izleme görüntülerinin sayfa numaraları. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | Ön izleme görüntülerinin biçimi. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | Ön izleme görüntülerinin DPI (inç başına nokta) cinsinden çözünürlüğü. Varsayılan çözünürlük 96 DPI'dir. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | Ön izleme görüntüsünün genişliği. |

### Örnek

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
`PreviewOptions` kullanan görev kılavuzları:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
