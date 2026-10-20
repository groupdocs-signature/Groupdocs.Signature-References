---
title: "FileType"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "表示文件类型。"
type: docs
weight: 610
url: /zh/net/groupdocs.signature.domain/filetype/
---
## FileType class

表示文件类型。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | 文件名后缀（包括句点 \".\"），例如 \".doc\"。 |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | 文件类型名称，例如 \"Microsoft Word Document\"。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | 将文件扩展名映射到文件类型。 |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | 确定当前的 [`FileType`](../filetype) 是否与指定的 [`FileType`](../filetype) 对象相同。 |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | 确定当前的 [`FileType`](../filetype) 是否与指定的对象相同。 |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | 返回当前 [`FileType`](../filetype) 对象的哈希码。 |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | 返回表示当前对象的字符串。 |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | 检索受支持的文件类型 |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | 确定两个 [`FileType`](../filetype) 对象是否相同。 |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | 确定两个 [`FileType`](../filetype) 对象是否不相同。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [APNG](../../groupdocs.signature.domain/filetype/apng) | Animated Portable Network Graphics (.png) 是一种使用无损压缩的光栅图像文件格式。它作为 PNG 的扩展而开发，以支持动画，作为没有版权限制的 GIF 格式的替代方案。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/apng)。 |
| static readonly [AZW3](../../groupdocs.signature.domain/filetype/azw3) | WordPerfect 文档 (.wpd) |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmap Image File (.bmp) 用于存储位图数字图像。这些图像独立于图形适配器，也称为设备无关位图（DIB）文件格式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/bmp)。 |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) 是一种使用 CorelDRAW 原生创建的矢量绘图图像文件，用于存储已编码和压缩的数字图像。此类绘图文件包含文本、线条、形状、图像、颜色和效果，以矢量方式表示图像内容。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/cdr)。 |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) 是一种免费、平台无关的国际标准元文件格式，用于存储和交换矢量图形（2D）、光栅图形和文本。CGM 采用面向对象的方法并提供多种功能用于图像生成。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/page-description-language/cgm)。 |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW 元文件交换图像文件 (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Comma Separated Values File (.csv) 表示包含逗号分隔值记录的纯文本文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/spreadsheet/csv)。 |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM Image (.dcm) 表示存储患者医学信息（如 MRI、CT 扫描和超声图像）的数字图像。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/dcm)。 |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Image (.djvu) 是一种针对扫描文档和书籍的图形文件格式，尤其适用于包含文本、图稿、图像和照片组合的内容。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/djvu)。 |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word Document (.doc) 表示由 Microsoft Word 或其他文字处理软件生成的二进制文件格式文档。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/doc)。 |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) 是由 Microsoft Word 2007 及以上版本生成的、具备运行宏功能的文档。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/docm)。 |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) 是 Microsoft Word 文档的知名格式。自 2007 年 Microsoft Office 2007 发布起，该文档格式的结构从纯二进制改为 XML 与二进制文件的组合。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/docx)。 |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word Document Template (.dot) 是由 Microsoft Word 创建的模板文件，具有预设的格式设置，用于生成后续的 DOC 或 DOCX 文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/dot)。 |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) 表示由 Microsoft Word 2007 及以上版本创建的模板文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/dotm)。 |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx) 是由 Microsoft Word 创建的模板文件，具有预设的格式设置，用于生成后续的 DOCX 文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/dotx)。 |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf) 以设备无关的方式表示图形图像。EMF 的元文件由按时间顺序排列的可变长度记录组成，可在任何输出设备上解析后渲染存储的图像。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/emf)。 |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript File (.eps) 描述了一个封装的 PostScript 语言程序，用于描述单页的外观。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/page-description-language/eps)。 |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File (.gif) 是一种高度压缩的图像类型。对于每张 GIF 图像，通常允许每像素最多 8 位，并且整个图像最多支持 256 种颜色。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/gif)。 |
| static readonly [GZip](../../groupdocs.signature.domain/filetype/gzip) | GZip compressed archive (.gz) 以高压缩比压缩文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/compression/gz)。 |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG Image (.jpeg) 是一种使用有损压缩方式保存的图像格式。压缩后的输出图像在存储大小和图像质量之间进行权衡。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/jpeg)。 |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG Image (.jpg) 是一种使用有损压缩方式保存的图像格式。压缩后的输出图像在存储大小和图像质量之间进行权衡。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/jpeg)。 |
| static readonly [LZip](../../groupdocs.signature.domain/filetype/lzip) | LZip compressed archive (.lz) 以高压缩比压缩文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/compression/lz)。 |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument Graphic File (.odg) 被 Apache OpenOffice 的 Draw 应用程序用于以矢量图像存储绘图元素。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/odg)。 |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp) 表示 OpenOffice.org 在 OASISOpen 标准中使用的演示文稿文件格式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/odp)。 |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) 代表可由用户编辑的 OpenDocument 电子表格文档格式。数据存储在 ODF 文件中，以行和列的形式组织。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/spreadsheet/ods)。 |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument Text Document (.odt) 是基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/odt)。 |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument Presentation Template (.otp) 表示使用 OASIS OpenDocument 标准格式的应用程序创建的演示文稿模板文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/otp)。 |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument 电子表格模板 (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument Document Template (.ott) 表示符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/ott)。 |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Printer Command Language 文档 (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf) 是 Adobe 在 1990 年代创建的一种文档类型。此文件格式的目的是引入一种独立于应用软件、硬件以及操作系统的文档和其他参考材料的标准表示方式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/view/pdf)。 |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Personal Information Exchange (.pfx) 文件是一种受密码保护的证书文件，常用于对您的应用程序进行代码签名。了解更多关于此文件格式的信息，请点击[here](https://fileinfo.com/extension/pfx)。 |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) 是一种使用无损压缩的栅格图像文件格式。该格式是为取代图形交换格式 (GIF) 而创建的，并且没有版权限制。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/png)。 |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint Template (.pot) 表示由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/pot)。 |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) 是支持宏的 Microsoft PowerPoint 模板文件。POTM 文件由 PowerPoint 2007 或更高版本创建，并包含可用于创建后续演示文稿的默认设置。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/potm)。 |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) 表示使用 Microsoft PowerPoint 2007 及以上版本创建的 Microsoft PowerPoint 模板演示文稿。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/potx)。 |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint Slide Show (.pps) 是使用 Microsoft PowerPoint 为幻灯片放映目的创建的文件。PPS 文件的读取和创建受 Microsoft PowerPoint 97-2003 支持。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/pps)。 |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) 表示由 Microsoft PowerPoint 2007 或更高版本创建的支持宏的幻灯片放映文件格式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/ppsm)。 |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) 文件是使用 Microsoft PowerPoint 2007 及以上版本为幻灯片放映目的创建的。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/ppsx)。 |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint Presentation (.ppt) 表示由 PowerPoint 组成的一系列幻灯片，用于以幻灯片放映方式显示。它指定了 Microsoft PowerPoint 97-2003 使用的二进制文件格式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/ppt)。 |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation 是由 Microsoft PowerPoint 2007 或更高版本创建的支持宏的演示文稿文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/pptm)。 |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文稿文件。不同于之前的二进制 PPT 格式，PPTX 基于 Microsoft PowerPoint 开放 XML 演示文稿文件格式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/presentation/pptx)。 |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript 文件 (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Document (.psd) 表示 Adobe Photoshop 的原生文件格式，用于图形设计和开发。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/psd)。 |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf) 表示一种用于在应用程序中编码格式化文本和图形的方法。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/word-processing/rtf)。 |
| static readonly [SevenZip](../../groupdocs.signature.domain/filetype/sevenzip) | High compressed archive (.7z) 使用高压缩比对文件和文件夹进行压缩。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/page-description-language/7z)。 |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) 是一种使用基于 XML 的文本格式来描述图像外观的可缩放矢量图形文件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/page-description-language/svg)。 |
| static readonly [TAR](../../groupdocs.signature.domain/filetype/tar) | Unix-based utility for collecting one or more files (.tar) 是一种可以容纳一个或多个文件或目录的归档文件。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/tar/)。 |
| static readonly [TGA](../../groupdocs.signature.domain/filetype/tga) | Truevision TGA (.tga)，亦称为 TARGA，是 Truevision Inc. 开发的栅格图像文件格式。它支持多种颜色深度和可选的 RLE 压缩。TGA 文件常用于视频游戏、动画流水线和图形应用程序，以实现高质量图像渲染并可选支持 alpha 通道。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/tga)。 |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Tagged Image File (.tif) 表示用于在符合此文件格式标准的各种设备上使用的光栅图像。它能够在多种色彩空间中描述二值、灰度、调色板颜色和全彩图像数据。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/tiff)。 |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) 表示用于在符合此文件格式标准的各种设备上使用的光栅图像。它能够在多种色彩空间中描述二值、灰度、调色板颜色和全彩图像数据。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/tiff)。 |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Tab Separated Values File (.tsv) 表示以制表符分隔的纯文本格式数据。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/tsv)。 |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Plain Text File (.txt) 表示包含以行为单位的纯文本的文本文档。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/txt)。 |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | 表示未知的文件类型。 |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard File (.vcf) 是一种用于存储联系信息的数字文件格式。该格式被广泛用于流行的信息交换应用程序之间的数据互通。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/email/vcf)。 |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) 是一种基于无损和有损压缩的现代光栅网页图像文件格式。它在显著减小图像尺寸的同时提供相同的图像质量。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/webp)。 |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf) 表示用于存储矢量以及位图格式图像数据的 Microsoft Windows Metafile (WMF)。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/wmf)。 |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect 文档 (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel Spreadsheet (.xls) 表示 Excel 二进制文件格式。这类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xls)。 |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) 指定 Excel 二进制文件格式，它是一组记录和结构，用于定义 Excel 工作簿的内容。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsb)。 |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) 是一种支持宏的电子表格文件类型。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsm)。 |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) 是一种广为人知的 Microsoft Excel 文档格式，随 Microsoft Office 2007 的发布而推出。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsx)。 |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel binary Template (.xlt) 表示 Excel 模板文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlt)。 |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML file Template (.xltm) 表示 Excel 模板文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xltm)。 |
| static readonly [ZIP](../../groupdocs.signature.domain/filetype/zip) | Document ZIP archive (.zip) 是一种支持无损数据压缩的归档文件格式。它可以容纳一个或多个文件或目录。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/compression/zip/)。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* More about how to get supported formats list in C#: [How to get supported file formats in C# code](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### 另请参见

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
