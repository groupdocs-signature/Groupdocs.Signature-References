---
title: "PdfMetadataSignature 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示 PDF 元数据签名。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/pdfmetadatasignature/
is_root: false
weight: 440
---


## PdfMetadataSignature class

表示 PDF 元数据签名。

PdfMetadataSignature 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name) | 使用预定义的名称和空值初始化 PDF 元数据签名。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name-value) | 使用预定义的值初始化 PDF 元数据签名。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#name-value-tag) | 使用预定义的值初始化 PDF 元数据签名。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/) | 克隆元数据签名实例。 |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/#value) | 使用给定的值克隆 PDF 元数据签名实例。 |
| [clone_object](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone_object/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/equals/#obj) | 根据属性比较此签名与另一个签名是否相等。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/get_hash_code/) | 返回签名的哈希码。 |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_boolean/) | 转换为布尔值。 (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/) | 将元数据签名值转换为日期时间。 (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_date_time_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_date_time_iformat_provider/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/) | 将元数据签名值转换为 Decimal。 (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_decimal_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_decimal_iformat_provider/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double/) | 将元数据签名值转换为浮点数。 (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_double_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_double_iformat_provider/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_integer](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_integer/) | 将元数据签名值转换为整数。 (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single/) | 将元数据签名值转换为浮点数。 (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_single_iformat_provider](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_single_iformat_provider/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string/) | 将元数据签名转换为字符串。 (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_file/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/metadatasignature/to_string_string/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [tag_prefix](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/tag_prefix/) | PDF 元数据签名名称的前缀标签。默认情况下此属性设置为 "xmp"。 |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 签名创建日期。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/data_encryption/) | 用于对签名值属性进行编码和解码的 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) 实现。 (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | 指示此签名是否已从文档中删除的标志。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 签名的高度。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | 指示此组件是表示签名 (`True`) 还是文档内容 (`False`) 的标志。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 签名的左侧位置。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 签名的修改日期。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [name](/signature/python-net/groupdocs.signature.domain/metadatasignature/name/) | 唯一的元数据名称。（继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)） |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 找到签名的页码。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 签名的唯一标识符，用于通过更新或删除操作修改文档中的签名。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 签名的类型。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 签名的顶部位置。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [type](/signature/python-net/groupdocs.signature.domain/metadatasignature/type/) | 元数据值的类型。（继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)） |
| [value](/signature/python-net/groupdocs.signature.domain/metadatasignature/value/) | 元数据对象。（继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)） |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 签名的宽度。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |

### 示例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
