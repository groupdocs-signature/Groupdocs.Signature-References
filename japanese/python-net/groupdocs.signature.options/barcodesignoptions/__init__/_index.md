---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "BarcodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

BarcodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#text}

BarcodeSignOptions クラスの新しいインスタンスをテキストで初期化します。

```python
def __init__(self, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 希望のテキストでバーコード署名オプションを作成する |

### 例

```python
from groupdocs.signature.options import BarcodeSignOptions

# バーコードエンコードタイプ。
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

BarcodeSignOptions クラスの新しいインスタンスをテキストで初期化します。

```python
def __init__(self, text, encode_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 希望のテキストでバーコード署名オプションを作成する |
| encode_type | `BarcodeType` | テキストとタイプを指定してバーコード署名オプションを作成する |

### 例

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# inner_margins プロパティ
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### 関連項目
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
