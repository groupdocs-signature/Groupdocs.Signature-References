---
title: "CertificateSearchOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示证书元数据签名的搜索选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/certificatesearchoptions/
is_root: false
weight: 60
---


## CertificateSearchOptions class

表示证书元数据签名的搜索选项。

了解更多

- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: Advanced search within Digital Certificate X509 documents (https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

CertificateSearchOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/) | 使用默认值初始化 TextSearchOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/#text) | 使用文本值初始化 TextSearchOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/match_type/) | 用于搜索的文本匹配类型。 |
| [text](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/text/) | 用于搜索匹配的证书属性文本。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 指示是否在每个文档页上进行搜索的标志。默认值为 True。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 用于搜索的文档页码（可选）。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 指定用于签名搜索的页面的选项。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 指示是否返回文档布局中形状位置的标志。仅适用于 Word 文档。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | 返回仅标记为 `IsSignature` 的签名的标志。默认值为 `False`，表示返回所有符合指定条件的签名。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
