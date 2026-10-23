---
title: "generate_signature_preview 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "根据给定的 SignOptions 生成签名预览。"
type: docs
url: /zh/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

根据给定的 SignOptions 生成签名预览。

了解更多关于如何生成签名预览的信息：
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | 使用给定 SignOptions 的预览签名。 |

### 示例

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # 将图像写入缓冲区而不是文件
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

### 另见
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
