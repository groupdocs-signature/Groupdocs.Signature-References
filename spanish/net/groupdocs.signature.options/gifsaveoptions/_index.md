---
title: "GifSaveOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Opciones de guardado en formato Gif para documentos de imagen."
type: docs
weight: 1610
url: /es/net/groupdocs.signature.options/gifsaveoptions/
---
## GifSaveOptions class

Opciones de guardado en formato Gif para documentos de imagen.

```csharp
public sealed class GifSaveOptions : ImageSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GifSaveOptions](gifsaveoptions)() | Crea GifSaveOptions con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es false. |
| [BackgroundColorIndex](../../groupdocs.signature.options/gifsaveoptions/backgroundcolorindex) { get; set; } | Obtiene o establece el índice de color de fondo del GIF. |
| [ColorResolution](../../groupdocs.signature.options/gifsaveoptions/colorresolution) { get; set; } | Obtiene o establece la resolución de color del GIF. |
| [DoPaletteCorrection](../../groupdocs.signature.options/gifsaveoptions/dopalettecorrection) { get; set; } | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [HasTrailer](../../groupdocs.signature.options/gifsaveoptions/hastrailer) { get; set; } | Obtiene o establece un valor que indica si el GIF tiene trailer. |
| [Interlaced](../../groupdocs.signature.options/gifsaveoptions/interlaced) { get; set; } | Verdadero si la imagen debe estar entrelazada. |
| [IsPaletteSorted](../../groupdocs.signature.options/gifsaveoptions/ispalettesorted) { get; set; } | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con el nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con un número como sufijo. Por defecto, este valor se establece en true, lo que significa que el archivo será sobrescrito. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. Esta propiedad no es compatible con documentos de imagen. |
| [PixelAspectRatio](../../groupdocs.signature.options/gifsaveoptions/pixelaspectratio) { get; set; } | Obtiene o establece la relación de aspecto de píxel del GIF. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si se usa la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es true. Esta propiedad no es compatible con documentos de imagen. |

### Ver también

* class [ImageSaveOptions](../imagesaveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
