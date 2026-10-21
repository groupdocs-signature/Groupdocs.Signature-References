---
title: "ExportImageSaveOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Opciones de guardado para exportar documentos a imagen."
type: docs
weight: 1580
url: /es/net/groupdocs.signature.options/exportimagesaveoptions/
---
## ExportImageSaveOptions class

Opciones de guardado para exportar documentos a imagen.

```csharp
public class ExportImageSaveOptions : ImageSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor)() | Inicializa una nueva instancia de la clase ExportAsImageSaveOptions con valores predeterminados. |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor_1)(ImageSaveFileFormat) | Inicializa una nueva instancia de la clase ExportAsImageSaveOptions con el formato de archivo especificado. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es false. |
| [Border](../../groupdocs.signature.options/exportimagesaveoptions/border) { get; set; } | Obtiene o establece la configuración del borde de la imagen. Por defecto, este valor no está establecido. |
| [ExportAllPages](../../groupdocs.signature.options/exportimagesaveoptions/exportallpages) { get; set; } | Indicador para exportar cada página. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con el nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con un número como sufijo. Por defecto, este valor se establece en true, lo que significa que el archivo será sobrescrito. |
| [PageColumns](../../groupdocs.signature.options/exportimagesaveoptions/pagecolumns) { get; set; } | Obtiene o establece el número de columnas para las imágenes exportadas. Use esta propiedad si necesita colocar imágenes en una fila. |
| [PageNumber](../../groupdocs.signature.options/exportimagesaveoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la exportación. El valor mínimo es 1. |
| [PagesSetup](../../groupdocs.signature.options/exportimagesaveoptions/pagessetup) { get; set; } | Opciones para especificar las páginas a firmar. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. Esta propiedad no es compatible con documentos de imagen. |
| [TiffMultipage](../../groupdocs.signature.options/exportimagesaveoptions/tiffmultipage) { get; set; } | Coloque las páginas del documento en diferentes marcos en una imagen Tiff. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si se usa la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es true. Esta propiedad no es compatible con documentos de imagen. |

### Ver también

* class [ImageSaveOptions](../imagesaveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
