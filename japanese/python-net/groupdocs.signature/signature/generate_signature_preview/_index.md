---
title: "generate_signature_preview メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "指定された SignOptions に基づいて署名プレビューを生成します。"
type: docs
url: /ja/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

指定された SignOptions に基づいて署名プレビューを生成します。

署名のプレビュー生成方法の詳細はこちら:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | 指定された SignOptions を使用したプレビュー署名。 |

### 例

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # 画像をファイルではなくバッファに書き込みます
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

### 関連項目
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
