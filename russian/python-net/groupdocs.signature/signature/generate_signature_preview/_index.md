---
title: "метод generate_signature_preview"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Создаёт предварительный просмотр подписи на основе заданных SignOptions."
type: docs
url: /ru/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

Создаёт предварительный просмотр подписи на основе заданных SignOptions.

Узнайте больше о том, как генерировать предварительные просмотры подписей:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | Предпросмотр подписи с заданными SignOptions. |

### Пример

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Записать изображение в буфер вместо файла
        return image

    sign_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
    sign_options.width = 120
    sign_options.height = 120

    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream)
    Signature.generate_signature_preview(preview_options)

    data = image.getvalue()
    is_png = data.startswith(b"\x89PNG")
    print(f"QR code preview: {len(data)} bytes, PNG image: {is_png}")

if __name__ == "__main__":
    generate_signature_preview_to_memory()
```

### См. также
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
