---
title: "TextSignature 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "TextSignature 类包含文本签名属性。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

TextSignature 类包含文本签名属性。

TextSignature 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | 使用从签名或搜索操作获得的唯一签名标识符初始化 TextSignature 对象。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | 克隆 Text Signature 实例。 |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | 比较指定的签名与此实例是否相等。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | 返回签名的哈希码。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | 指示签名是否特定于文档的本机属性。 |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | 文本签名实现。 |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | 签名的文本。 |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | 签名创建日期。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | 指示此签名是否已从文档中删除的标志。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | 签名的高度。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | 指示此组件是表示签名 (`True`) 还是文档内容 (`False`) 的标志。 (继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | 签名的左侧位置。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | 签名的修改日期。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | 找到签名的页码。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | 签名的唯一标识符，用于通过更新或删除操作修改文档中的签名。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | 签名的类型。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | 签名的顶部位置。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | 签名的宽度。（继承自 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
