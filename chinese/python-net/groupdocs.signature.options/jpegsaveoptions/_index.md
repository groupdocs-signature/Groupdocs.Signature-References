---
title: "JpegSaveOptions 类"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "表示图像文档的 JPEG 保存选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

表示图像文档的 JPEG 保存选项。

JpegSaveOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | 使用默认值初始化 JpegSaveOptions。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | 无损 JPEG 图像每通道的位数。支持的值范围为每通道 2 到 8 位。 |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | JPEG 图像的颜色类型。 |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | JPEG 文件注释。 |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | 压缩类型。 |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | 图像质量。 |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | 用于将 8 位值适配到 `JpegOptions.BitsPerChannel` 的 n 位值的采样舍入模式。 |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | 标志决定是否在输出文件路径缺少扩展名时自动添加扩展名。默认值为 False。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | 已签名文档的文件格式。（继承自 [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)） |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | 标志指示是否用新输出文件覆盖已有文件。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | 用于保护已保存已签名文档的密码。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | 标志指示在将已签名文档保存为受保护时是否使用来自 [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) 的密码。默认值为 True。图像文档不支持此功能。（继承自 [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)） |

### 另见
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
