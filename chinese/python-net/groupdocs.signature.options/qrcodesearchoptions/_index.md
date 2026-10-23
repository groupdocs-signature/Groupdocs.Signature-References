---
title: "QrCodeSearchOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示 QR 码签名的搜索选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

表示 QR 码签名的搜索选项。

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

QrCodeSearchOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | 使用默认值初始化 QRCodeSearchOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | 使用编码类型值初始化 QRCodeSearchOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | 使用编码类型和文本值初始化 QRCodeSearchOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | 实现用于对 QR-Code 签名文本或数据属性进行编码和解码的 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/)。 |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | 用于搜索 QR 码的编码类型。 |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | 搜索期间使用的 QR-Code 文本匹配类型。 |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | 标志决定是否为文档页上的每个签名返回 QR‑Code 图像内容。设置为 True 时，原始图像数据会保存在签名的 `content` 属性中，使用 `return_content_type` 指定的格式。默认情况下禁用。 |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | 当启用 `return_content` 属性时，QR-Code 签名返回的图像内容的文件类型。 |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | 用于搜索和匹配的 QR-Code 签名文本。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 指示是否在每个文档页上进行搜索的标志。默认值为 True。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 用于搜索的文档页码（可选）。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 指定用于签名搜索的页面的选项。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 指示是否返回文档布局中形状位置的标志。仅适用于 Word 文档。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | 返回仅标记为 `IsSignature` 的签名的标志。默认值为 `False`，表示返回所有符合指定条件的签名。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
