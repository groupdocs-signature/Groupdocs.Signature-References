---
title: "DigitalSearchOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示数字签名的搜索选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

表示数字签名的搜索选项。

了解更多

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

DigitalSearchOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | 使用默认值初始化 DigitalSearchOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | 要搜索的数字签名的注释。 |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | 当值不为空时，要搜索的证书颁发者的可辨识名称。 |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | 要搜索的数字签名的日期和时间范围。可为空的值将被忽略。 |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | 要搜索的数字签名的日期时间范围的结束。空值将被忽略。 |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | 当提供非空值时，要搜索的证书的可辨别主题名称。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 指示是否在每个文档页上进行搜索的标志。默认值为 True。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 用于搜索的文档页码（可选）。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 指定用于签名搜索的页面的选项。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 指示是否返回文档布局中形状位置的标志。仅适用于 Word 文档。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | 返回仅标记为 `IsSignature` 的签名的标志。默认值为 `False`，表示返回所有符合指定条件的签名。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
