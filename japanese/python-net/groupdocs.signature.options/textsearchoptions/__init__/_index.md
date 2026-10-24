---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "`TextSearchOptions` クラスの新しいインスタンスをデフォルト値で初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

`TextSearchOptions` クラスの新しいインスタンスをデフォルト値で初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # デフォルトオプションを使用してテキスト署名を検索します
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

`TextSearchOptions` クラスの新しいインスタンスをテキスト値で初期化します。

```python
def __init__(self, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | テキスト署名のテキストです。 |

### 関連項目
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
