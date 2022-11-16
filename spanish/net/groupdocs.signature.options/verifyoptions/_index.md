---
title: VerifyOptions
second_title: Referencia de API de GroupDocs.Signature para .NET
description: Mantiene opciones para verificar documento.
type: docs
weight: 1700
url: /es/net/groupdocs.signature.options/verifyoptions/
---
## VerifyOptions class

Mantiene opciones para verificar documento.

```csharp
public abstract class VerifyOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Bandera para verificar cada página del documento. Por defecto el valor es true. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Extensiones adicionales para la verificación de opciones de firma alternativas. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Bandera de propiedad válida. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Número de página del documento a verificar. Si la propiedad no está configurada, todas las páginas del documento se verificarán por primera vez. El valor mínimo es 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Opciones de página para especificar las páginas que se verificarán. |

### Ver también

* espacio de nombres [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* asamblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->