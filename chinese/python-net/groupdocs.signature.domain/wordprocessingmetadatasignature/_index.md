---
title: "WordProcessingMetadataSignature 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示文字处理元数据签名。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/
is_root: false
weight: 840
---


## WordProcessingMetadataSignature class

表示文字处理元数据签名。

与 [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) 一起使用，以向 Word Processing 文档添加元数据签名。

WordProcessingMetadataSignature 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/#name) | 使用指定的名称和空值初始化 WordProcessingMetadataSignature。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/#name-value) | 使用预定义值初始化 WordProcessing 元数据签名。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/clone/) | 克隆元数据签名实例。 |
| [clone](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/clone/#value) | 使用指定的值创建 WordProcessingMetadataSignature 实例的克隆。 |
| [clone_object](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/clone_object/) |  |
| [to_string](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/) | 将元数据签名转换为字符串。 |
| [to_string](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/#format-provider) | 将元数据签名转换为具有指定格式的字符串。 |
| [to_string_file](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string_file/) |  |
| [to_string_string](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string_string/) |  |
| [equals](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals/) | 确定指定的签名是否等于此实例。（继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)） |
| [equals_object](/signature/python-net/groupdocs.signature.domain/metadatasignature/equals_object/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_data_idata_encryption/) | (继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)) |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/metadatasignature/get_hash_code/) | 返回元数据签名的哈希码。（继承自 [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)） |
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

### 属性
| 属性 | 描述 |
| :- | :- |
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
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes"),
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
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
