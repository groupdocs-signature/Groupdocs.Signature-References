---
title: "PreviewOptions класс"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры предварительного просмотра документа."
type: docs
url: /ru/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

Представляет параметры предварительного просмотра документа.

Тип PreviewOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | Высота изображений предварительного просмотра. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | Флаг, указывающий, скрыты ли подписи на изображениях предварительного просмотра страниц. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | Номера страниц изображений предварительного просмотра. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | Формат изображений предварительного просмотра. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | Разрешение изображений предварительного просмотра в DPI (точек на дюйм). Разрешение по умолчанию — 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | Ширина изображения предварительного просмотра. |

### Пример

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
Руководства задач, использующие `PreviewOptions`:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
