---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "QRCodeSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

QRCodeSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

QRCodeSearchOptions クラスの新しいインスタンスをエンコードタイプの値で初期化します。

```python
def __init__(self, encode_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| encode_type | `QrCodeType` | QR-Code エンコードタイプを指定します。 |

## __init__ {#encode_type-text}

QRCodeSearchOptions クラスの新しいインスタンスをエンコードタイプとテキストの値で初期化します。

```python
def __init__(self, encode_type, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| encode_type | `QrCodeType` | QR-Code エンコードタイプを指定します。 |
| text | `str` | QR-Code 署名のテキストを設定します。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### 関連項目
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
