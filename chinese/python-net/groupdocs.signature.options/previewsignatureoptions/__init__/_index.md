---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "初始化一个 PreviewSignatureOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

初始化一个 PreviewSignatureOptions 实例。

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sign_options | `SignOptions` | 用于生成预览的签名选项。 |
| create_signature_stream | `CreateSignatureStream` | 创建输出签名预览流的委托。 |

### 示例

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# 用于接收预览图像的内存缓冲区
preview_buffer = io.BytesIO()

def create_stream(options):
    # 对任何预览生成返回相同的缓冲区
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# 将预览图像生成到缓冲区中
Signature.generate_signature_preview(preview_opts)

# 访问生成的 PNG 字节
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

初始化一个 PreviewSignatureOptions 对象。

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sign_options | `SignOptions` | 用于生成预览的签名选项。 |
| create_signature_stream | `CreateSignatureStream` | 创建输出签名预览流的可调用对象。它接收签名选项并应返回一个 `io.RawIOBase`（例如，`io.BytesIO`）。 |
| release_signature_stream | `ReleaseSignatureStream` | 释放输出签名预览流的可调用对象。它接收签名选项和流，并执行任何必要的清理。 |

### 示例

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

### 另见
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
