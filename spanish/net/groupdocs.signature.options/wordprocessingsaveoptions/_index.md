---
title: WordProcessingSaveOptions
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Opciones de guardado para documentos de WordProcessing.
type: docs
weight: 1790
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
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(bool) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el tipo de salida especificado y el indicador de sobrescritura. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_2)(WordProcessingSaveFileFormat) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con el formato de archivo de salida especificado. |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_3)(WordProcessingSaveFileFormat, bool) | Inicializa una nueva instancia de la clase WordProcessingSaveOptions con formato de archivo de salida especificado y marca de sobrescritura. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Obtiene o establece el indicador para agregar automáticamente la extensión cuando faltaba en la ruta del archivo de salida El valor predeterminado es false. |
| [FileFormat](../../groupdocs.signature.options/wordprocessingsaveoptions/fileformat) { get; set; } | Obtiene o establece el formato de archivo del documento firmado. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Obtiene o establece si se sobrescribe el archivo existente con un nuevo archivo de salida. De lo contrario, se creará un nuevo archivo con el número como sufijo. De forma predeterminada, este valor se establece en verdadero, lo que significa que se sobrescribirá el archivo. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Obtiene o establece la contraseña para guardar el documento firmado con protección de contraseña. Esta propiedad no es compatible con los documentos de imagen. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Obtiene o establece si usar la contraseña de LoadOptions para guardar el documento firmado como protegido. El valor predeterminado es verdadero. Esta propiedad no se admite para documentos de imagen. |

### Ver también

* class [SaveOptions](../saveoptions)
* espacio de nombres [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
