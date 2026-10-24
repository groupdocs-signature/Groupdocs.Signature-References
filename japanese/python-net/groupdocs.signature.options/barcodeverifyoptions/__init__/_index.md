---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "バーコード署名のデフォルト検証オプションを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

バーコード署名のデフォルト検証オプションを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

検証テキストを使用したデフォルト検証オプションを初期化します。

```python
def __init__(self, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 検証するバーコードテキストです。 |

## __init__ {#encode_type}

バーコードタイプの検証を使用したデフォルト検証オプションを初期化します。

```python
def __init__(self, encode_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| encode_type | `BarcodeType` | バーコードタイプの検証です。 |

## __init__ {#text-encode_type}

バーコードタイプの検証とテキストを使用したデフォルト検証オプションを初期化します。

```python
def __init__(self, text, encode_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 検証するバーコードテキストです。 |
| encode_type | `BarcodeType` | バーコードタイプの検証です。 |

### 関連項目
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
