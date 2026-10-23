---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用指定的名称和空值初始化 WordProcessingMetadataSignature。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

使用指定的名称和空值初始化 WordProcessingMetadataSignature。

```python
def __init__(self, name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | WordProcessing Metadata Signature 名称。 |

### 示例

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# 使用名称和值创建元数据签名。
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

使用预定义值初始化 WordProcessing 元数据签名。

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### 另见
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
