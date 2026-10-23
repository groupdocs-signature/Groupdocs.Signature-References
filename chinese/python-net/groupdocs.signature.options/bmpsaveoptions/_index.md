---
title: "BmpSaveOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示图像文档的 BMP 保存选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 50
---


## BmpSaveOptions class

表示图像文档的 BMP 保存选项。

BmpSaveOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/) | 使用默认值初始化 BmpSaveOptions。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel/) | 图像每像素位数。 |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression/) | 压缩方式。参见 `BitmapCompression`。 |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution/) | 水平分辨率。请注意，由于四舍五入，实际分辨率可能与设定值略有差异。 |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution/) | 垂直分辨率；请注意，由于四舍五入，实际分辨率可能与设定值略有差异。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 标志决定是否在输出文件路径缺少扩展名时自动添加扩展名。默认值为 False。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 已签名文档的文件格式。（继承自 [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)） |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 标志指示是否用新输出文件覆盖已有文件。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 用于保护已保存已签名文档的密码。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 标志指示在将已签名文档保存为受保护时是否使用来自 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 的密码。默认值为 True。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
