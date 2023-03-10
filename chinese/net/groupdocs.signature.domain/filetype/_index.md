---
title: FileType
second_title: GroupDocs.Signature for .NET API 参考
description: 代表文件类型
type: docs
weight: 450
url: /zh/net/groupdocs.signature.domain/filetype/
---
## FileType class

代表文件类型。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | 文件名后缀（包括句点“.”）例如“.doc”. |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | 文件类型名称，例如“Microsoft Word 文档”. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | 将文件扩展名映射到文件类型。 |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | 判断当前是否[`FileType`](../filetype)与指定的相同[`FileType`](../filetype)对象. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | 判断当前是否[`FileType`](../filetype)与指定对象相同。 |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | 返回当前的哈希码[`FileType`](../filetype)对象. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | 返回表示当前对象的字符串。 |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | 检索支持的文件类型 |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | 判断是否两个[`FileType`](../filetype)对象是相同的。 |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | 判断是否两个[`FileType`](../filetype)对象不一样. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | 位图图像文件 (.bmp) 用于存储位图数字图像。这些图像独立于图形适配器，也称为设备独立位图 (DIB) 文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/bmp) |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) 是使用 CorelDRAW 原生创建的矢量绘图图像文件，用于存储编码和压缩的数字图像。这样的绘图文件包含用于图像内容的矢量表示的文本、线条、形状、图像、颜色和效果。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/cdr) |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | 计算机图形图元文件 (.cgm) 是一种免费的、独立于平台的国际标准图元文件格式，用于存储和交换矢量图形 (2D)、光栅图形和文本。 CGM 使用面向对象的方法和许多图像制作功能规定。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/page-description-language/cgm) |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW 图元文件交换图像文件 (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | 逗号分隔值文件 (.csv) 表示纯文本文件，其中包含以逗号分隔值的数据记录。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/csv) |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM 图像 (.dcm) 表示存储患者医疗信息的数字图像，例如 MRI、CT 扫描和超声图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/dcm) |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu 图像 (.djvu) 是一种图形文件格式，适用于扫描的文档和书籍，尤其是那些包含文本、绘图、图像和照片的组合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/djvu) |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word 文档 (.doc) 表示由 Microsoft Word 或其他文字处理文档以二进制文件格式生成的文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/doc) |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) 是 Microsoft Word 2007 或更高版本生成的文档，能够运行宏。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/docm) |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML 文档 (.docx) 是一种众所周知的 Microsoft Word 文档格式。随着 Microsoft Office 2007 的发布从 2007 年引入，这种新文档格式的结构从普通二进制文件更改为 XML 和二进制文件的组合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/docx) |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word 文档模板 (.dot) 是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOC 或 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dot) |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML 启用宏的文档模板 (.dotm) 表示使用 Microsoft Word 2007 或更高版本创建的模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dotm) |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML 文档模板 (.dotx) 是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dotx) |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | 增强型 Windows 图元文件 (.emf) 独立于设备表示图形图像。 EMF 的元文件由按时间顺序排列的可变长度记录组成，可以在任何输出设备上解析后呈现存储的图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/emf) |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | 封装的 PostScript 文件 (.eps) 描述了一个封装的 PostScript 语言程序，它描述了单个页面的外观。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/page-description-language/eps) |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | 图形交换格式文件 (.gif) 是一种高度压缩的图像。对于每个图像，GIF 通常允许每个像素最多 8 位，并且整个图像最多允许 256 种颜色。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/gif) |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG 图像 (.jpeg) 是一种使用有损压缩方法保存的图像格式。作为压缩的结果，输出图像是存储大小和图像质量之间的权衡。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/jpeg) |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG 图像 (.jpg) 是一种使用有损压缩方法保存的图像格式。作为压缩的结果，输出图像是存储大小和图像质量之间的权衡。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/jpeg) |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument 图形文件 (.odg) 由 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/odg) |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp) 表示 OpenOffice.org 在 OASISOpen 标准中使用的演示文稿文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/odp) |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument 电子表格 (.ods) 代表用户可编辑的 OpenDocument 电子表格文档格式。数据以行和列的形式存储在 ODF 文件中。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/ods) |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument 文本文档 (.odt) 是使用基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/odt) |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument 演示模板 (.otp) 表示应用程序以 OASIS OpenDocument 标准格式创建的演示模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/otp) |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument 电子表格模板 (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument 文档模板 (.ott) 表示由应用程序生成的符合 OASIS 的 OpenDocument 标准格式的模板文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/ott) |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | 打印机命令语言文档 (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | 便携式文档格式文件 (.pdf) 是 Adobe 在 1990 年代创建的一种文档。这种文件格式的目的是引入一种标准，以一种独立于应用程序软件、硬件和操作系统的格式来表示文档和其他参考资料。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/view/pdf) |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | 可缩放矢量图形文件 (.svg) 是一种标量矢量图形文件，它使用基于 XML 的文本格式来描述图像的外观。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/page-description-language/svg) |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | 便携式网络图形 (.png) 是一种使用无损压缩的光栅图像文件格式。此文件格式是为替代图形交换格式 (GIF) 而创建的，没有版权限制。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/png) |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint 模板 (.pot) 表示由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pot) |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML 启用宏的演示模板 (.potm) 是支持宏的 Microsoft PowerPoint 模板文件。 POTM 文件是使用 PowerPoint 2007 或更高版本创建的，包含可用于创建更多演示文稿文件的默认设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potm) |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML 演示文稿模板 (.potx) 表示使用 Microsoft PowerPoint 2007 及更高版本创建的 Microsoft PowerPoint 模板演示文稿。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potx) |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint 幻灯片放映 (.pps) 是使用 Microsoft PowerPoint 创建的，用于放映幻灯片。 Microsoft PowerPoint 97-2003 支持 PPS 文件读取和创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pps) |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML 启用宏的幻灯片 (.ppsm) 表示使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的幻灯片放映文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsm) |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML 幻灯片放映 (.ppsx) 文件是使用 Microsoft PowerPoint 2007 及更高版本创建的，用于放映幻灯片。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsx) |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint 演示文稿 (.ppt) 代表 PowerPoint 文件，该文件由一组幻灯片组成，用于显示为 SlideShow。它指定 Microsoft PowerPoint 97-2003 使用的二进制文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppt) |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML 启用宏的演示文稿是使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的演示文稿文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptm) |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML 演示文稿 (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文稿文件。与以前版本的二进制演示文稿文件格式 PPT 不同，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文稿文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptx) |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript 文件 (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop 文档 (.psd) 代表 Adobe Photoshop 用于图形设计和开发的本机文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/psd) |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf) 表示一种编码格式化文本和图形以在应用程序中使用的方法。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/rtf) |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | 可缩放矢量图形文件 (.svg) 是一种标量矢量图形文件，它使用基于 XML 的文本格式来描述图像的外观。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/page-description-language/svg) |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | 标记图像文件 (.tif) 表示适用于符合此文件格式标准的各种设备的光栅图像。它能够在多个颜色空间中描述二值、灰度、调色板颜色和全色图像数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/tiff) |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | 标记图像文件格式 (.tiff) 表示适用于符合此文件格式标准的各种设备的光栅图像。它能够在多个颜色空间中描述二值、灰度、调色板颜色和全色图像数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/tiff) |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | 制表符分隔值文件 (.tsv) 表示以纯文本格式的制表符分隔的数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/tsv) |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | 纯文本文件 (.txt) 表示包含行形式的纯文本的文本文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/txt) |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | 代表未知文件类型。 |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard 文件 (.vcf) 是一种用于存储联系人信息的数字文件格式。该格式广泛用于流行信息交换应用程序之间的数据交换。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/vcf) |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP 图像 (.webp) 是一种基于无损和有损压缩的现代光栅网络图像文件格式。它提供相同的图像质量，同时显着减小图像尺寸。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/webp) |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows 图元文件 (.wmf) 表示用于存储矢量和位图格式图像数据的 Microsoft Windows 图元文件 (WMF)。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/wmf) |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect 文档 (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel 电子表格 (.xls) 表示 Excel 二进制文件格式。此类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（例如 OpenOffice Calc 或 Apple Numbers）创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel 二进制电子表格 (.xlsb) 指定 Excel 二进制文件格式，它是指定 Excel 工作簿内容的记录和结构的集合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsb) |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) 是一种支持宏的电子表格文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsm) |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML 电子表格 (.xlsx) 是 Microsoft 随 Microsoft Office 2007 发布而引入的一种众所周知的 Microsoft Excel 文档格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsx) |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel 二进制模板 (.xlt) 表示 Excel 模板文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlt) |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML 文件模板 (.xltm) 表示 Excel 模板文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xltm) |

### 评论

**了解更多**

* 有关 GroupDocs 支持的文件类型的更多信息。签名： [GroupDocs.Signature 支持的文档格式](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* 有关如何在 C# 中获取支持的格式列表的更多信息： [如何在 C# 代码中获取支持的文件格式](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### 也可以看看

* 命名空间 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
