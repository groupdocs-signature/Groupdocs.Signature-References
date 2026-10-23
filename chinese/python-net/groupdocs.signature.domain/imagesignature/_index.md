---
title: "ImageSignature 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "该类包含图像签名属性。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

该类包含图像签名属性。

ImageSignature 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | 使用从 [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/) 类的 Sign 或 Search 方法获取的唯一签名标识符初始化 ImageSignature 对象。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | 克隆 ImageSignature 实例。 |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | 确定指定的签名是否等于此实例。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | 返回签名的哈希码。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | 签名的二进制图像数据，采用 [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) 指定的格式。 |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | 签名图像的格式。 |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | 签名图像的字节大小。 |
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
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
