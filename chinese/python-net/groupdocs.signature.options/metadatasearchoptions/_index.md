---
title: "MetadataSearchOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示元数据签名的搜索选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

表示元数据签名的搜索选项。

提供用于配置在文档中搜索元数据签名的选项。

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

MetadataSearchOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | 使用默认值初始化 MetadataSearchOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | 实现了用于解密此选项集合中所有元数据签名的 [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/)。 |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | 标志指示是否在搜索结果中包含内置文档属性，如文档统计信息和其他信息。 |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | 要搜索和匹配的元数据签名名称。 |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | 用于搜索的元数据名称匹配类型。仅在设置了 `name` 属性时才会应用。 |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | 指示是否在每个文档页上进行搜索的标志。默认值为 True。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | 用于搜索的文档页码（可选）。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | 指定用于签名搜索的页面的选项。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | 指示是否返回文档布局中形状位置的标志。仅适用于 Word 文档。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | 返回仅标记为 `IsSignature` 的签名的标志。默认值为 `False`，表示返回所有符合指定条件的签名。（继承自 [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    options = MetadataSearchOptions()
    options.name = "Author"
    options.name_match_type = TextMatchType.EXACT

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching metadata signature(s)")
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value}")
```

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
