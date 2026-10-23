---
title: "SearchResult 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示在指定文档中搜索签名的结果。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

表示在指定文档中搜索签名的结果。

SearchResult 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | 返回搜索结果的迭代器。 |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | 目标文档大小，对于 Search 方法始终为 0。 |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | 未通过搜索条件的签名列表 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。 |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | 搜索过程的执行时间（毫秒）。 |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | 找到的签名列表 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。 |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | 源文档大小。 |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | 找到的签名列表（[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)）。 |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | 搜索过程返回的已处理签名的总数。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### 另见
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
