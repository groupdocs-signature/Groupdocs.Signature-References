---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用预定义名称初始化 PdfTextFormFieldSignature。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

使用预定义名称初始化 PdfTextFormFieldSignature。

```python
def __init__(self, name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | 表单字段对象的名称。 |

### 示例

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

使用预定义名称初始化 PdfTextFormFieldSignature。

```python
def __init__(self, name, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | 表单字段对象的名称。 |
| text | `str` | 表单字段对象的文本。 |

### 示例

```python
from groupdocs.signature.domain import TextFormFieldSignature

# 创建一个名为 "FieldText"、值为 "Value1" 的文本表单字段
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### 另见
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
