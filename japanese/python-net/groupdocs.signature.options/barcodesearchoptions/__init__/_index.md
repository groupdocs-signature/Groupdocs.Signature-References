---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "BarcodeSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

BarcodeSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature.options import BarcodeSearchOptions

# デフォルト設定の検索オプションオブジェクトを作成する
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

エンコード タイプの値を使用して BarcodeSearchOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self, encode_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| encode_type | `BarcodeType` | バーコードのエンコードタイプを指定します。 |

## __init__ {#encode_type-text}

エンコード タイプとテキストの値を使用して BarcodeSearchOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self, encode_type, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| encode_type | `BarcodeType` | バーコードのエンコードタイプを指定します。 |
| text | `str` | バーコード署名のテキストを設定します。 |

### 関連項目
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
