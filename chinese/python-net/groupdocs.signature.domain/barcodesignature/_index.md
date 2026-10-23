---
title: "BarcodeSignature 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示条形码签名。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/barcodesignature/
is_root: false
weight: 20
---


## BarcodeSignature class

表示条形码签名。

BarcodeSignature 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/barcodesignature/__init__/#signature_id) | 使用在搜索过程后获得的签名标识符初始化 BarcodeSignature 对象。该标识符用于从文档的签名信息层检索此签名的其他属性。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/barcodesignature/clone/) | 克隆 Barcode Signature 实例。 |
| [equals](/signature/python-net/groupdocs.signature.domain/barcodesignature/equals/#obj) | 比较此条形码签名与另一个签名是否相等。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain/barcodesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/barcodesignature/get_hash_code/) | 返回条形码签名的哈希码。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/barcodesignature/content/) | 条形码二进制数据图像内容采用由 [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) 指定的格式。 |
| [encode_type](/signature/python-net/groupdocs.signature.domain/barcodesignature/encode_type/) | 条形码编码类型。 |
| [format](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) | 条形码签名图像的格式。 |
| [text](/signature/python-net/groupdocs.signature.domain/barcodesignature/text/) | 条形码的文本。 |
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

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
