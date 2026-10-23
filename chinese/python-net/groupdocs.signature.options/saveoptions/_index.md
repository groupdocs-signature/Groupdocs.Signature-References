---
title: "SaveOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "在保存文档以进行签名时指定附加选项（例如密码）。"
type: docs
url: /zh/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

在保存文档以进行签名时指定附加选项（例如密码）。

SaveOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | 使用默认值初始化 SaveOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | 使用指定的输出类型和覆盖标志初始化 SaveOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 标志决定在输出文件路径缺少扩展名时是否自动添加扩展名。默认值为 False。 |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 标志指示是否用新输出文件覆盖已有文件。 |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 用于保护已保存的已签名文档的密码。Image 文档不支持此功能。 |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 标志指示在将已签名文档保存为受保护时是否使用来自 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 的密码。默认值为 True。Image 文档不支持此功能。 |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
