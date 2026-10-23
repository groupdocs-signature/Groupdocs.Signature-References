---
title: "PdfSaveOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示 PDF 文档的保存选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

表示 PDF 文档的保存选项。

PdfSaveOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | 使用默认值初始化 PdfSaveOptions 的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | 使用指定的输出文件格式初始化 PdfSaveOptions 的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | 使用覆盖标志初始化 PdfSaveOptions 的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | 使用指定的输出文件格式和覆盖标志初始化 PdfSaveOptions 的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | 已签署文档的文件格式。 |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | PDF 文档的权限，例如打印、修改和数据提取。 |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | 更改权限设置所需的权限密码（主密码）。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 标志决定是否在输出文件路径缺少扩展名时自动添加扩展名。默认值为 False。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 标志指示是否用新输出文件覆盖已有文件。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 用于保护已保存已签名文档的密码。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 标志指示在将已签名文档保存为受保护时是否使用来自 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 的密码。默认值为 True。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
