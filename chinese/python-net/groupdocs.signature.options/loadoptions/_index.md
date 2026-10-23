---
title: "LoadOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "LoadOptions 类允许在打开文档进行签名时指定附加选项（例如密码）。"
type: docs
url: /zh/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

LoadOptions 类允许在打开文档进行签名时指定附加选项（例如密码）。

如果文件已加密，将 `password` 属性设置为文档密码。

LoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | 初始化 LoadOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | 使用指定的文件类型初始化 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | 与加载选项关联的文件类型，默认为 [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/)。 |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | 决定文档是否加载外部资源的标志。此属性已过时；请改用 [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/)，其含义相反。 |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | 用于打开受保护文档以及将已签名文档另存为受保护状态的密码。 |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | PDF 文档的权限，例如打印、修改和数据提取。仅适用于 PDF 文档。 |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | 阻止文档加载外部资源的标志。默认值为 True；除匹配 [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) 的资源外，外部资源均不加载。 |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | 即使 [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) 为 true，也会加载的外部资源地址片段列表。默认值为空列表。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
