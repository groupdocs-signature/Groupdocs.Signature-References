---
title: "TextSearchOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示文本签名的搜索选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

表示文本签名的搜索选项。

了解更多：
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

TextSearchOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | 使用默认值初始化 TextSearchOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | 使用文本值初始化 TextSearchOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | 用于搜索的文本匹配类型。 |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | 要搜索的文本签名实现。 |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | 搜索时匹配的签名文本。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 指示是否在每个文档页上进行搜索的标志。默认值为 True。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 用于搜索的文档页码（可选）。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 指定用于签名搜索的页面的选项。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 指示是否返回文档布局中形状位置的标志。仅适用于 Word 文档。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | 返回仅标记为 `IsSignature` 的签名的标志。默认值为 `False`，表示返回所有符合指定条件的签名。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    options = TextSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.text = "John"
    options.match_type = TextMatchType.CONTAINS
    options.signature_implementation = TextSignatureImplementation.NATIVE

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching text signature(s)")
    for ts in result.signatures:
        print(f"'{ts.text}' on page {ts.page_number} at ({ts.left}, {ts.top}), size {ts.width}x{ts.height}")
```

### Guides
使用 `TextSearchOptions` 的任务指南：

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
