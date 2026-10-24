---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "QrCodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

QrCodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#text}

指定されたテキストで QR コード署名オプションのインスタンスを初期化します。

```python
def __init__(self, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 署名テキスト。 |

### 例

```python
from groupdocs.signature.options import QrCodeSignOptions

# 希望するテキストで QR コード署名オプションを作成する
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

テキストを使用して QrCodeSignOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self, text, encode_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | QRコードのテキスト。 |
| encode_type | `QrCodeType` | QRコードのエンコードタイプ。 |

### 例

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### 関連項目
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
