---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用预定义的名称和空值初始化 PDF 元数据签名。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

使用预定义的名称和空值初始化 PDF 元数据签名。

```python
def __init__(self, name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | PDF 元数据签名名称。 |

## __init__ {#name-value}

使用预定义的值初始化 PDF 元数据签名。

```python
def __init__(self, name, value):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | 元数据签名对象的名称。 |
| value | `Any` | 元数据签名的值。 |

### 示例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

使用预定义的值初始化 PDF 元数据签名。

```python
def __init__(self, name, value, tag):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | 元数据签名对象的名称。 |
| value | `Any` | 元数据签名的值。 |
| tag | `str` | 元数据签名的前缀标签。 |

### 示例

```python
from groupdocs.signature.domain import PdfMetadataSignature

# 为 PDF 作者创建元数据签名
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# 为创建日期创建元数据签名
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# 为数值标识符创建元数据签名
id_sig = PdfMetadataSignature("DocumentId", 123456)

# 为浮点值创建元数据签名
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### 另见
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
