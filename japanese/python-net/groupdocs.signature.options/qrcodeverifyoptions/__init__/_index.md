---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "QR コード署名の検証オプションを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

QR コード署名の検証オプションを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

指定された QR コードテキストを使用して QR コード署名の検証オプションを初期化します。

```python
def __init__(self, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 検証対象の QR コードテキスト。 |

### 例

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# オプションを作成し、検証対象の QR コードテキストを設定します。
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

テキストと QR コードエンコードタイプを指定して QR コード署名の検証オプションを初期化します。

```python
def __init__(self, text, encode_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 検証対象のテキストです。 |
| encode_type | `QrCodeType` | エンコーディングの種類。 |

### 例

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### 関連項目
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
