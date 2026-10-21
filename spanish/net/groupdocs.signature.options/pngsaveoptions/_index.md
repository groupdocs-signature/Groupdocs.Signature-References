---
title: "PngSaveOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Opciones de guardado PNG para documentos de imagen."
type: docs
weight: 1820
url: /es/net/groupdocs.signature.options/pngsaveoptions/
---
## PngSaveOptions class

Opciones de guardado PNG para documentos de imagen.

```csharp
public sealed class PngSaveOptions : ImageSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PngSaveOptions](pngsaveoptions)() | Crea PngSaveOptions con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es false. |
| [BitDepth](../../groupdocs.signature.options/pngsaveoptions/bitdepth) { get; set; } | La profundidad de bits. |
| [ColorType](../../groupdocs.signature.options/pngsaveoptions/colortype) { get; set; } | Obtiene o establece el tipo de [`PngColorType`](../pngcolortype). |
| [CompressionLevel](../../groupdocs.signature.options/pngsaveoptions/compressionlevel) { get; set; } | El nivel de compresión de la imagen png en el rango 0-9, donde 9 es la máxima compresión y 0 es modo de almacenamiento. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [FilterType](../../groupdocs.signature.options/pngsaveoptions/filtertype) { get; set; } | Obtiene o establece el tipo de filtro [`PngFilterType`](../pngfiltertype) utilizado durante el proceso de guardado de archivos png. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con el nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con un número como sufijo. Por defecto, este valor se establece en true, lo que significa que el archivo será sobrescrito. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. Esta propiedad no es compatible con documentos de imagen. |
| [Progressive](../../groupdocs.signature.options/pngsaveoptions/progressive) { get; set; } | Obtiene o establece un valor que indica si este PngSaveOptions es progresivo. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si se usa la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es true. Esta propiedad no es compatible con documentos de imagen. |

### Ver también

* class [ImageSaveOptions](../imagesaveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
