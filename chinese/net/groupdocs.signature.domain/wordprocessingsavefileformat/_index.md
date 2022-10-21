---
title: WordProcessingSaveFileFormat
second_title: GroupDocs.Signature for .NET API 参考
description: 为文字处理文档定义不同的保存文件格式
type: docs
weight: 1050
url: /zh/net/groupdocs.signature.domain/wordprocessingsavefileformat/
---
## WordProcessingSaveFileFormat enumeration

为文字处理文档定义不同的保存文件格式。

```csharp
public enum WordProcessingSaveFileFormat
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Default | `0` | 文件格式不会改变。 |
| Doc | `1` | 将文档另存为 Microsoft Word 97-2003 文档。 |
| Dot | `2` | 将文档另存为 Microsoft Word 97-2003 模板。 |
| Docx | `3` | 将文档另存为 Microsoft Word OpenXML 文档。 |
| Docm | `4` | 将文档另存为 Microsoft Word OpenXML 启用宏的文档。 |
| Dotx | `5` | 将文档另存为 Microsoft Word OpenXML 模板。 |
| Dotm | `6` | 将文档另存为 Microsoft Word OpenXML 启用宏的模板。 |
| FlatOpc | `24` | 将文档另存为 Office Open XML WordprocessingML ，存储在平面 XML 文件而不是 ZIP 包中。 |
| FlatOpcMacroEnabled | `25` | 将文档另存为 Office Open XML WordprocessingML 启用宏的文档，存储在平面 XML 文件而不是 ZIP 包中。 |
| FlatOpcTemplate | `26` | 将文档另存为 Office Open XML WordprocessingML 模板（无宏），存储在平面 XML 文件而不是 ZIP 包中。 |
| FlatOpcTemplateMacroEnabled | `27` | 将文档另存为 Office Open XML WordprocessingML 启用宏的模板，存储在平面 XML 文件而不是 ZIP 包中。 |
| Rtf | `30` | 以 RTF 格式保存文档。所有 7 位以上的字符都被转义为十六进制或 Unicode 字符。 |
| WordML | `31` | 以 Microsoft Word 2003 WordprocessingML 格式保存文档。 |
| Pdf | `40` | 将文档另存为 PDF（Adobe 便携式文档）格式。 |
| Xps | `41` | 以 XPS（XML 纸张规范）格式保存文档。 |
| Ps | `47` | 以 PS (PostScript) 格式保存文档。 |
| Mhtml | `51` | 以 MHTML（Web 存档）格式保存文档。 |
| Epub | `52` | 以 IDPF EPUB 格式保存文档。 |
| Odt | `60` | 将文档另存为 Open Office 文档。 |
| Ott | `61` | 将文档另存为 Open Office 文档模板。 |
| Text | `70` | 以纯文本格式保存文档。 |
| Tiff | `100` | 渲染文档的一页或多页并将它们保存到单页或多页 TIFF 文件中。 |
| Png | `101` | 呈现文档页面并将其保存为 PNG 文件。 |
| Bmp | `102` | 渲染文档页面并将其保存为 BMP 文件。 |
| Emf | `103` | 渲染文档页面并将其保存为矢量 EMF（增强元文件）文件。 |
| Jpeg | `104` | 渲染文档页面并将其保存为 JPEG 文件。 |

### 也可以看看

* 命名空间 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->