---
title: "BarcodeSearchOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示条形码签名的搜索选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

表示条形码签名的搜索选项。

了解更多：
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

BarcodeSearchOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | 使用默认值初始化 BarcodeSearchOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | 使用编码类型值初始化 BarcodeSearchOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | 使用编码类型和文本值初始化 BarcodeSearchOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | 用于过滤条形码搜索的编码类型；如果未设置，搜索将包括所有支持的条形码类型。 |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | 用于搜索的条形码文本匹配类型。仅在设置了 `text` 属性时使用。 |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | 指示是否检索文档页上签名的条形码图像内容的标志。 |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | 当启用 `return_content` 属性时，条形码签名返回的图像内容的文件类型。 |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | 要搜索和匹配的条形码签名文本。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 指示是否在每个文档页上进行搜索的标志。默认值为 True。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 用于搜索的文档页码（可选）。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 指定用于签名搜索的页面的选项。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 指示是否返回文档布局中形状位置的标志。仅适用于 Word 文档。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | 返回仅标记为 `IsSignature` 的签名的标志。默认值为 `False`，表示返回所有符合指定条件的签名。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
使用 `BarcodeSearchOptions` 的任务指南：

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
