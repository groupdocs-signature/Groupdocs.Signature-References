---
title: "QrCodeSignature 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示 QR 码签名属性。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/qrcodesignature/
is_root: false
weight: 550
---


## QrCodeSignature class

表示 QR 码签名属性。

QrCodeSignature 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/qrcodesignature/__init__/#signature_id) | 使用在搜索过程后获得的签名标识符初始化 QrCodeSignature 对象。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/qrcodesignature/clone/) | 克隆 QR-Code 签名实例。 |
| [equals](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals/#obj) | 确定给定的签名对象是否等于此实例。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals_object/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/#data_encryption) |  |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data_idata_encryption/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_hash_code/) | 重写 GetHashCode 方法。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/qrcodesignature/content/) | QR-code 二进制数据图像内容，类型为 [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/)。 |
| [encode_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/encode_type/) | QR-code 编码类型。 |
| [format](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) | QR-code 签名图像的格式。 |
| [text](/signature/python-net/groupdocs.signature.domain/qrcodesignature/text/) | QR-code 的文本。 |
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
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    if result.signatures:
        qr = result.signatures[0]
        print(qr.text, qr.encode_type.type_name, qr.left, qr.top)
```

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
