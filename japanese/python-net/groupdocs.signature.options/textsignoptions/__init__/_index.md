---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルト値で TextSignOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

デフォルト値で TextSignOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#text}

テキストで TextSignOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 署名テキスト。 |

### 例

```python
from groupdocs.signature.options import TextSignOptions

# 目的の署名テキストでテキスト署名オプションを作成します
options = TextSignOptions("John Smith")
```

### 関連項目
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
