---
title: "ImageSaveOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示图像文档的保存选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/imagesaveoptions/
is_root: false
weight: 230
---


## ImageSaveOptions class

表示图像文档的保存选项。

ImageSaveOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/) | 使用默认值初始化 ImagesSaveOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#overwrite_existing_file) | 使用覆盖标志初始化 ImagesSaveOptions 类的新实例。 |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#file_format-overwrite_existing_file) | 使用指定的输出文件格式和覆盖标志初始化 ImagesSaveOptions 的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 已签署文档的文件格式。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 标志决定是否在输出文件路径缺少扩展名时自动添加扩展名。默认值为 False。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 标志指示是否用新输出文件覆盖已有文件。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 用于保护已保存已签名文档的密码。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 标志指示在将已签名文档保存为受保护时是否使用来自 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 的密码。默认值为 True。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
