---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "PreviewSignatureOptions のインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

PreviewSignatureOptions のインスタンスを初期化します。

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| sign_options | `SignOptions` | プレビューを生成する署名オプションです。 |
| create_signature_stream | `CreateSignatureStream` | 出力署名プレビュー ストリームを作成するデリゲート。 |

### 例

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# プレビュー画像を受け取るためのメモリバッファ
preview_buffer = io.BytesIO()

def create_stream(options):
    # 任意のプレビュー生成に対して同じバッファを返す
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# プレビュー画像をバッファに生成する
Signature.generate_signature_preview(preview_opts)

# 生成された PNG バイトにアクセスする
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

PreviewSignatureOptions オブジェクトを初期化します。

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| sign_options | `SignOptions` | プレビューを生成する署名オプションです。 |
| create_signature_stream | `CreateSignatureStream` | 出力署名プレビュー ストリームを作成する呼び出し可能オブジェクト。署名オプションを受け取り、`io.RawIOBase`（例: `io.BytesIO`）を返す必要があります。 |
| release_signature_stream | `ReleaseSignatureStream` | 出力署名プレビュー ストリームを解放する呼び出し可能オブジェクト。署名オプションとストリームを受け取り、必要なクリーンアップを実行します。 |

### 例

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

### 関連項目
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
