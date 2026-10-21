---
title: "JpegSaveOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Opciones de guardado Jpeg para documentos de imagen."
type: docs
weight: 1710
url: /es/net/groupdocs.signature.options/jpegsaveoptions/
---
## JpegSaveOptions class

Opciones de guardado Jpeg para documentos de imagen.

```csharp
public sealed class JpegSaveOptions : ImageSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [JpegSaveOptions](jpegsaveoptions)() | Crea JpegSaveOptions con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es false. |
| [BitsPerChannel](../../groupdocs.signature.options/jpegsaveoptions/bitsperchannel) { get; set; } | Obtiene o establece los bits por canal para una imagen jpeg sin pérdida. Ahora soportamos de 2 a 8 bits por canal. |
| [ColorType](../../groupdocs.signature.options/jpegsaveoptions/colortype) { get; set; } | Obtiene o establece el tipo de color para la imagen jpeg. |
| [Comment](../../groupdocs.signature.options/jpegsaveoptions/comment) { get; set; } | Obtiene o establece el comentario del archivo jpeg. |
| [CompressionType](../../groupdocs.signature.options/jpegsaveoptions/compressiontype) { get; set; } | Obtiene o establece el tipo de compresión. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con el nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con un número como sufijo. Por defecto, este valor se establece en true, lo que significa que el archivo será sobrescrito. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. Esta propiedad no es compatible con documentos de imagen. |
| [Quality](../../groupdocs.signature.options/jpegsaveoptions/quality) { get; set; } | Obtiene o establece la calidad de la imagen. |
| [SampleRoundingMode](../../groupdocs.signature.options/jpegsaveoptions/sampleroundingmode) { get; set; } | Obtiene o establece el modo de redondeo de la muestra para ajustar un valor de 8 bits a un valor de n bits JpegOptions.BitsPerChannel. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si se usa la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es true. Esta propiedad no es compatible con documentos de imagen. |

### Ver también

* class [ImageSaveOptions](../imagesaveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
