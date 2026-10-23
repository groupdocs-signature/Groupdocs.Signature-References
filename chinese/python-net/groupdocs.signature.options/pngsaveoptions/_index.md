---
title: "PngSaveOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示图像文档的 PNG 保存选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 400
---


## PngSaveOptions class

表示图像文档的 PNG 保存选项。

PngSaveOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/) | 使用默认值初始化 PngSaveOptions。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth/) | 位深度。 |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type/) | `PngColorType` 的类型。 |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level/) | png 图像的压缩级别，范围为 0-9，其中 9 为最高压缩，0 为存储模式。 |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type/) | 在 PNG 文件保存过程中使用的过滤器类型 `PngFilterType`。 |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive/) | 指示 PNG 是否逐步保存的 progressive 标志。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 标志决定是否在输出文件路径缺少扩展名时自动添加扩展名。默认值为 False。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 已签名文档的文件格式。（继承自 [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)） |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 标志指示是否用新输出文件覆盖已有文件。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 用于保护已保存已签名文档的密码。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 标志指示在将已签名文档保存为受保护时是否使用来自 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 的密码。默认值为 True。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
