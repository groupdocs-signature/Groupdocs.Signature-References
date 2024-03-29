---
title: PngSaveOptions
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Opciones de guardado de png para documentos de imagen.
type: docs
weight: 1560
url: /es/net/groupdocs.signature.options/pngsaveoptions/
---
## PngSaveOptions class

Opciones de guardado de png para documentos de imagen.

```csharp
public sealed class PngSaveOptions : ImageSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PngSaveOptions](pngsaveoptions)() | Crea PngSaveOptions con valores predeterminados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece el indicador para agregar automáticamente la extensión cuando faltaba en la ruta del archivo de salida El valor predeterminado es false. |
| [BitDepth](../../groupdocs.signature.options/pngsaveoptions/bitdepth) { get; set; } | La profundidad de bits. |
| [ColorType](../../groupdocs.signature.options/pngsaveoptions/colortype) { get; set; } | Obtiene o establece el tipo de la[`PngColorType`](../pngcolortype) . |
| [CompressionLevel](../../groupdocs.signature.options/pngsaveoptions/compressionlevel) { get; set; } | El nivel de compresión de la imagen png en el rango 0-9, donde 9 es la compresión máxima y 0 es el modo de almacenamiento. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [FilterType](../../groupdocs.signature.options/pngsaveoptions/filtertype) { get; set; } | Obtiene o establece el tipo de filtro[`PngFilterType`](../pngfiltertype) utilizado durante el proceso de guardado del archivo png. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con un nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con el número como sufijo. De forma predeterminada, este valor se establece en verdadero, lo que significa que se sobrescribirá el archivo. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección de contraseña. Esta propiedad no es compatible con los documentos de imagen. |
| [Progressive](../../groupdocs.signature.options/pngsaveoptions/progressive) { get; set; } | Obtiene o establece un valor que indica si este PngSaveOptions es progresivo. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si usar la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es verdadero. Esta propiedad no se admite para documentos de imagen. |

### Ver también

* class [ImageSaveOptions](../imagesaveoptions)
* espacio de nombres [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
