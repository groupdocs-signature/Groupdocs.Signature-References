---
title: GifSaveOptions
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Opciones de guardado en formato gif para documentos de imagen.
type: docs
weight: 1390
url: /es/net/groupdocs.signature.options/gifsaveoptions/
---
## GifSaveOptions class

Opciones de guardado en formato gif para documentos de imagen.

```csharp
public sealed class GifSaveOptions : ImageSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GifSaveOptions](gifsaveoptions)() | Crea GifSaveOptions con valores predeterminados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece el indicador para agregar automáticamente la extensión cuando faltaba en la ruta del archivo de salida El valor predeterminado es false. |
| [BackgroundColorIndex](../../groupdocs.signature.options/gifsaveoptions/backgroundcolorindex) { get; set; } | Obtiene o establece el índice de color de fondo del GIF. |
| [ColorResolution](../../groupdocs.signature.options/gifsaveoptions/colorresolution) { get; set; } | Obtiene o establece la resolución de color del GIF. |
| [DoPaletteCorrection](../../groupdocs.signature.options/gifsaveoptions/dopalettecorrection) { get; set; } | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [HasTrailer](../../groupdocs.signature.options/gifsaveoptions/hastrailer) { get; set; } | Obtiene o establece un valor que indica si el GIF tiene tráiler. |
| [Interlaced](../../groupdocs.signature.options/gifsaveoptions/interlaced) { get; set; } | Verdadero si la imagen debe estar entrelazada. |
| [IsPaletteSorted](../../groupdocs.signature.options/gifsaveoptions/ispalettesorted) { get; set; } | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con un nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con el número como sufijo. De forma predeterminada, este valor se establece en verdadero, lo que significa que se sobrescribirá el archivo. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección de contraseña. Esta propiedad no es compatible con los documentos de imagen. |
| [PixelAspectRatio](../../groupdocs.signature.options/gifsaveoptions/pixelaspectratio) { get; set; } | Obtiene o establece la proporción de aspecto de píxeles del GIF. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si usar la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es verdadero. Esta propiedad no se admite para documentos de imagen. |

### Ver también

* class [ImageSaveOptions](../imagesaveoptions)
* espacio de nombres [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
