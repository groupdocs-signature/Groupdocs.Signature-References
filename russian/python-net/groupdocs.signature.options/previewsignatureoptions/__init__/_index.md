---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует экземпляр PreviewSignatureOptions."
type: docs
url: /ru/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Инициализирует экземпляр PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| sign_options | `SignOptions` | Параметры подписи, для которых генерируется предварительный просмотр. |
| create_signature_stream | `CreateSignatureStream` | Делегат, который создает поток предварительного просмотра выходной подписи. |

### Пример

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Буфер памяти для получения изображения предварительного просмотра.
preview_buffer = io.BytesIO()

def create_stream(options):
    # Возвращать тот же буфер для любого создания предварительного просмотра.
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Создавать изображение предварительного просмотра в буфер.
Signature.generate_signature_preview(preview_opts)

# Получить доступ к сгенерированным байтам PNG.
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Инициализирует объект PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| sign_options | `SignOptions` | Параметры подписи, для которых генерируется предварительный просмотр. |
| create_signature_stream | `CreateSignatureStream` | Вызываемый объект, который создает поток предварительного просмотра выходной подписи. Он получает параметры подписи и должен возвращать `io.RawIOBase` (например, `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | Вызываемый объект, который освобождает поток предварительного просмотра выходной подписи. Он получает параметры подписи и поток и выполняет необходимую очистку. |

### Пример

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_qr_code_image():
    result = io.BytesIO()
    qr_options = QrCodeSignOptions()
    qr_options.encode_type = QrCodeTypes.QR
    qr_options.text = "Case 148-01"

    preview_options = PreviewSignatureOptions(
        qr_options,
        lambda options: result,
        lambda options, stream: None,
    )
    Signature.generate_signature_preview(preview_options)

    with open("qr_code_result.png", "wb") as f:
        f.write(result.getvalue())
```

### См. также
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
