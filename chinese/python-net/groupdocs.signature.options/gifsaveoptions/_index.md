---
title: "GifSaveOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示图像文档的 GIF 格式保存选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/gifsaveoptions/
is_root: false
weight: 190
---


## GifSaveOptions class

表示图像文档的 GIF 格式保存选项。

GifSaveOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/gifsaveoptions/__init__/) | 使用默认值初始化 GifSaveOptions。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [background_color_index](/signature/python-net/groupdocs.signature.options/gifsaveoptions/background_color_index/) | GIF 背景颜色索引。 |
| [color_resolution](/signature/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/) | GIF 颜色分辨率。 |
| [do_palette_correction](/signature/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/) | 指示是否应用调色板校正的标志。 |
| [has_trailer](/signature/python-net/groupdocs.signature.options/gifsaveoptions/has_trailer/) | 指示 GIF 是否包含尾部的标志。 |
| [interlaced](/signature/python-net/groupdocs.signature.options/gifsaveoptions/interlaced/) | 当设置为 True 时，图像为隔行扫描。 |
| [is_palette_sorted](/signature/python-net/groupdocs.signature.options/gifsaveoptions/is_palette_sorted/) | 指示调色板条目是否已排序的值。 |
| [pixel_aspect_ratio](/signature/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/) | GIF 像素宽高比。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 标志决定是否在输出文件路径缺少扩展名时自动添加扩展名。默认值为 False。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 已签名文档的文件格式。（继承自 [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)） |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 标志指示是否用新输出文件覆盖已有文件。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 用于保护已保存已签名文档的密码。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 标志指示在将已签名文档保存为受保护时是否使用来自 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 的密码。默认值为 True。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
