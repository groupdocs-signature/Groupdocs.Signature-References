---
title: "BmpSaveOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Opciones de guardado Bmp para documentos de imagen."
type: docs
weight: 1480
url: /es/net/groupdocs.signature.options/bmpsaveoptions/
---
## BmpSaveOptions class

Opciones de guardado Bmp para documentos de imagen.

```csharp
public sealed class BmpSaveOptions : ImageSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BmpSaveOptions](bmpsaveoptions)() | Crea BmpSaveOptions con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es false. |
| [BitsPerPixel](../../groupdocs.signature.options/bmpsaveoptions/bitsperpixel) { get; set; } | Obtiene o establece el recuento de bits por píxel de la imagen. |
| [Compression](../../groupdocs.signature.options/bmpsaveoptions/compression) { get; set; } | Obtiene o establece la compresión. Ver [`BitmapCompression`](../bitmapcompression). |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [HorizontalResolution](../../groupdocs.signature.options/bmpsaveoptions/horizontalresolution) { get; set; } | Obtiene o establece la resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con el nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con un número como sufijo. Por defecto, este valor se establece en true, lo que significa que el archivo será sobrescrito. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. Esta propiedad no es compatible con documentos de imagen. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si se usa la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es true. Esta propiedad no es compatible con documentos de imagen. |
| [VerticalResolution](../../groupdocs.signature.options/bmpsaveoptions/verticalresolution) { get; set; } | Obtiene o establece la resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |

### Ver también

* class [ImageSaveOptions](../imagesaveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
