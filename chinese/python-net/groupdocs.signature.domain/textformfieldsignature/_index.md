---
title: "TextFormFieldSignature 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示 PDF 文档的文本输入表单字段签名属性。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

表示 PDF 文档的文本输入表单字段签名属性。

TextFormFieldSignature 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | 使用预定义名称初始化 PdfTextFormFieldSignature。 |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | 使用预定义名称初始化 PdfTextFormFieldSignature。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | 克隆 FormField Signature 实例。 |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | 根据类型和属性值比较此签名与另一个签名是否相等。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | 重写 GetHashCode 方法。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | 表单字段输入的文本。 |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 签名创建日期。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | 指示此签名是否已从文档中删除的标志。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 签名的高度。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | 指示此组件是表示签名 (`True`) 还是文档内容 (`False`) 的标志。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 签名的左侧位置。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 签名的修改日期。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | 唯一的表单字段名称。（继承自 [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)） |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 找到签名的页码。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 签名的唯一标识符，用于通过更新或删除操作修改文档中的签名。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 签名的类型。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 签名的顶部位置。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | 表单字段类型。（继承自 [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)） |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | 表单字段数据对象。（继承自 [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)） |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 签名的宽度。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # 创建一个名为 "FieldText"、值为 "Value1" 的文本表单字段
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # 为其创建表单字段选项
        options = FormFieldSignOptions(text_field)

        # 设置表单字段的位置和大小
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # 对文档进行签名并保存结果
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
