---
title: "WordProcessingSaveOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Opciones de guardado para documentos de WordProcessing."
type: docs
weight: 2080
url: /es/net/groupdocs.signature.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Opciones de guardado para documentos de WordProcessing.

```csharp
public class WordProcessingSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con valores predeterminados. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(bool) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el tipo de salida especificado y la bandera de sobrescritura. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_2)(WordProcessingSaveFileFormat) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el formato de archivo de salida especificado. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_3)(WordProcessingSaveFileFormat, bool) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el formato de archivo de salida especificado y la bandera de sobrescritura. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece la bandera para agregar automáticamente la extensión cuando falta en la ruta del archivo de salida. El valor predeterminado es false. |
| [FileFormat](../../groupdocs.signature.options/wordprocessingsaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [OoxmlCompliance](../../groupdocs.signature.options/wordprocessingsaveoptions/ooxmlcompliance) { get; set; } | Nivel de cumplimiento OOXML opcional para el documento firmado. Cuando se establece, sobrescribe el cumplimiento del documento original. Cuando es nulo (predeterminado), se conserva el cumplimiento del documento cargado. Sólo se aplica a formatos OOXML (Docx, Docm, Dotx, Dotm, FlatOpc y variantes FlatOpc). |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con el nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con un número como sufijo. Por defecto, este valor se establece en true, lo que significa que el archivo será sobrescrito. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección por contraseña. Esta propiedad no es compatible con documentos de imagen. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si se usa la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es true. Esta propiedad no es compatible con documentos de imagen. |

### Ver también

* class [SaveOptions](../saveoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
