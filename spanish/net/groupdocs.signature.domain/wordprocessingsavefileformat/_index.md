---
title: "WordProcessingSaveFileFormat"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Define diferentes formatos de archivo para guardar documentos de WordProcessing."
type: docs
weight: 1270
url: /es/net/groupdocs.signature.domain/wordprocessingsavefileformat/
---
## WordProcessingSaveFileFormat enumeration

Define diferentes formatos de archivo para guardar documentos de WordProcessing.

```csharp
public enum WordProcessingSaveFileFormat
```

### Values

| Nombre | Value | Descripción |
| --- | --- | --- |
| Default | `0` | El formato de archivo no se cambiará. |
| Doc | `1` | Guarda el documento como documento de Microsoft Word 97-2003. |
| Dot | `2` | Guarda el documento como plantilla de Microsoft Word 97-2003. |
| Docx | `3` | Guarda el documento como documento Microsoft Word OpenXML. |
| Docm | `4` | Guarda el documento como documento Microsoft Word OpenXML con macros habilitadas. |
| Dotx | `5` | Guarda el documento como plantilla Microsoft Word OpenXML. |
| Dotm | `6` | Guarda el documento como plantilla Microsoft Word OpenXML con macros habilitadas. |
| FlatOpc | `24` | Guarda el documento como un Office Open XML WordprocessingML almacenado en un archivo XML plano en lugar de un paquete ZIP. |
| FlatOpcMacroEnabled | `25` | Guarda el documento como un Office Open XML WordprocessingML Documento con Macros Habilitadas almacenado en un archivo XML plano en lugar de un paquete ZIP. |
| FlatOpcTemplate | `26` | Guarda el documento como una plantilla Office Open XML WordprocessingML (sin macros) almacenada en un archivo XML plano en lugar de un paquete ZIP. |
| FlatOpcTemplateMacroEnabled | `27` | Guarda el documento como una plantilla Office Open XML WordprocessingML con Macros Habilitadas almacenada en un archivo XML plano en lugar de un paquete ZIP. |
| Rtf | `30` | Guarda el documento en formato RTF. Todos los caracteres superiores a 7 bits se escapan como caracteres hexadecimales o Unicode. |
| WordML | `31` | Guarda el documento en el formato Microsoft Word 2003 WordprocessingML. |
| Pdf | `40` | Guarda el documento como formato PDF (Adobe Portable Document). |
| Xps | `41` | Guarda el documento en el formato XPS (Especificación de Papel XML). |
| Ps | `47` | Guarda el documento en el formato PS (PostScript). |
| Mhtml | `51` | Guarda el documento en el formato MHTML (archivo web). |
| Epub | `52` | Guarda el documento en el formato IDPF EPUB. |
| Odt | `60` | Guarda el documento como documento Open Office. |
| Ott | `61` | Guarda el documento como plantilla de documento Open Office. |
| Text | `70` | Guarda el documento en formato de texto plano. |
| Tiff | `100` | Renderiza una o varias páginas del documento y las guarda en un archivo TIFF de una sola página o multipágina. |
| Png | `101` | Renderiza una página del documento y la guarda como archivo PNG. |
| Bmp | `102` | Renderiza una página del documento y la guarda como archivo BMP. |
| Emf | `103` | Renderiza una página del documento y la guarda como archivo vectorial EMF (Enhanced Meta File). |
| Jpeg | `104` | Renderiza una página del documento y la guarda como archivo JPEG. |
| Azw3 | `105` | Renderiza una página del documento y la guarda como archivo Azw3. |

### Ver también

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
