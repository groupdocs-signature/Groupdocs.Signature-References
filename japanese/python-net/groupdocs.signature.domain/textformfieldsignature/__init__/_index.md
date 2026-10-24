---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "事前定義された名前で PdfTextFormFieldSignature を初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

事前定義された名前で PdfTextFormFieldSignature を初期化します。

```python
def __init__(self, name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | `str` | フォーム フィールド オブジェクトの名前。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

with Signature("sample.pdf") as signature:
    text_field = TextFormFieldSignature("FieldText", "Value1")
    options = FormFieldSignOptions(text_field)
    options.left = 100
    options.top = 400
    options.width = 200
    options.height = 20
    result = signature.sign("signed_form_field.pdf", options)
    for field in result.succeeded:
        print(f"Added form field '{field.name}' with value '{field.value}'")
```

## __init__ {#name-text}

事前定義された名前で PdfTextFormFieldSignature を初期化します。

```python
def __init__(self, name, text):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | `str` | フォーム フィールド オブジェクトの名前。 |
| text | `str` | フォームフィールドオブジェクトのテキスト。 |

### 例

```python
from groupdocs.signature.domain import TextFormFieldSignature

# 名前が "FieldText" で値が "Value1" のテキスト フィールドを作成します
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### 関連項目
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
