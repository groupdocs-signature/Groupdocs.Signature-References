---
title: "clone 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "克隆元数据签名实例。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

克隆元数据签名实例。

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### 示例

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # 克隆具有新值的标准元数据签名
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

使用给定的值克隆 PDF 元数据签名实例。

```python
def clone(self, value):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | `Any` | 新克隆对象的值。 |

**Returns:** A cloned metadata signature instance.

### 示例

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# 克隆现有元数据签名并赋予新值
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### 另见
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
