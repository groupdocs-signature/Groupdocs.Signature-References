---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "`TextVerifyOptions` の新しいインスタンスをデフォルト値で初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/textverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

`TextVerifyOptions` の新しいインスタンスをデフォルト値で初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## __init__ {#text}

`TextVerifyOptions` の新しいインスタンスを検証テキストで初期化します。

```python
def __init__(self, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 検証対象のテキストです。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

## __init__ {#text-implementation}

検証するテキストと署名実装タイプを指定して、新しい TextVerifyOptions インスタンスを初期化します。

```python
def __init__(self, text, implementation):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 検証対象のテキストです。 |
| implementation | `TextSignatureImplementation` | 署名実装タイプです。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

### 関連項目
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)
