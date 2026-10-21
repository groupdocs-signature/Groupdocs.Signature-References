---
title: "SpreadsheetSaveOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Opciones de guardado para documentos de hoja de cálculo."
type: docs
weight: 1990
url: /es/net/groupdocs.signature.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Opciones de guardado para documentos de hoja de cálculo.

```csharp
public class SpreadsheetSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | Inicializa una nueva instancia de la clase SpreadsheetSaveOptions con valores predeterminados. |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetSaveFileFormat) | Inicializa una nueva instancia de la clase SpreadsheetSaveOptions con un formato de archivo de salida predefinido. |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_2)(SpreadsheetSaveFileFormat, bool) | Inicializa una nueva instancia de la clase SpreadsheetSaveOptions con el tipo de salida especificado y la bandera de sobrescritura. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es false. |
| [FileFormat](../../groupdocs.signature.options/spreadsheetsaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con el nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con un número como sufijo. Por defecto, este valor se establece en true, lo que significa que el archivo será sobrescrito. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. Esta propiedad no es compatible con documentos de imagen. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si se usa la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es true. Esta propiedad no es compatible con documentos de imagen. |

### Ver también

* class [SaveOptions](../saveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
