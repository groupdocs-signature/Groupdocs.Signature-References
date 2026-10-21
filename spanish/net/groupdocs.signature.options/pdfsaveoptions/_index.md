---
title: "PdfSaveOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Opciones de guardado para documentos PDF."
type: docs
weight: 1760
url: /es/net/groupdocs.signature.options/pdfsaveoptions/
---
## PdfSaveOptions class

Opciones de guardado para documentos PDF.

```csharp
public class PdfSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions#constructor)() | Inicializa una nueva instancia de la clase PdfSaveOptions con valores predeterminados. |
| [PdfSaveOptions](pdfsaveoptions#constructor_1)(bool) | Inicializa una nueva instancia de la clase PdfSaveOptions con la bandera de sobrescritura. |
| [PdfSaveOptions](pdfsaveoptions#constructor_2)(PdfSaveFileFormat) | Inicializa una nueva instancia de la clase PdfSaveOptions con el formato de archivo de salida especificado. |
| [PdfSaveOptions](pdfsaveoptions#constructor_3)(PdfSaveFileFormat, bool) | Inicializa una nueva instancia de la clase PdfSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es false. |
| [FileFormat](../../groupdocs.signature.options/pdfsaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con el nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con un número como sufijo. Por defecto, este valor se establece en true, lo que significa que el archivo será sobrescrito. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. Esta propiedad no es compatible con documentos de imagen. |
| [Permissions](../../groupdocs.signature.options/pdfsaveoptions/permissions) { get; set; } | Los permisos del documento PDF, como impresión, modificación y extracción de datos. |
| [PermissionsPassword](../../groupdocs.signature.options/pdfsaveoptions/permissionspassword) { get; set; } | Una contraseña de permisos (la contraseña principal) requiere una contraseña para cambiar la configuración de permisos. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si se usa la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es true. Esta propiedad no es compatible con documentos de imagen. |

### Ver también

* class [SaveOptions](../saveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
