---
title: "LoadOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Permite especificar opciones adicionales como la contraseña al abrir un documento para firmar."
type: docs
weight: 1720
url: /es/net/groupdocs.signature.options/loadoptions/
---
## LoadOptions class

Permite especificar opciones adicionales (como la contraseña) al abrir un documento para firmar.

```csharp
public class LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Inicializa una nueva instancia de la clase LoadOptions. |
| [LoadOptions](loadoptions#constructor_1)(FileType) | Inicializa una nueva instancia de la clase [`LoadOptions`](../loadoptions) con un tipo de archivo especificado. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [FileType](../../groupdocs.signature.options/loadoptions/filetype) { get; set; } | Obtiene o establece el tipo de archivo asociado con las opciones de carga. |
| [Password](../../groupdocs.signature.options/loadoptions/password) { get; set; } | Obtiene o establece la contraseña para abrir un documento protegido. También se usará para guardar el documento firmado como protegido. |
| [Permissions](../../groupdocs.signature.options/loadoptions/permissions) { get; } | Los permisos del documento PDF, como impresión, modificación y extracción de datos. Solo para documentos PDF. |
| [SkipExternalResources](../../groupdocs.signature.options/loadoptions/skipexternalresources) { get; set; } | Obtiene o establece una bandera que impide que el documento cargue recursos externos. El valor predeterminado es true: los recursos externos no se cargan, excepto aquellos que coinciden con [`WhitelistedResources`](./whitelistedresources). |
| [WhitelistedResources](../../groupdocs.signature.options/loadoptions/whitelistedresources) { get; set; } | Obtiene o establece fragmentos de direcciones de recursos externos que se cargan incluso cuando [`SkipExternalResources`](./skipexternalresources) es true. El valor predeterminado es una lista vacía. |

### Ver también

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
