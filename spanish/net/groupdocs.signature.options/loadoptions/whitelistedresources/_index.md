---
title: "WhitelistedResources"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Obtiene o establece fragmentos de direcciones de recursos externos que se cargan incluso cuando SkipExternalResourcesgroupdocs.signature.options/loadoptions/skipexternalresources es true. El valor predeterminado es una lista vacía."
type: docs
weight: 60
url: /es/net/groupdocs.signature.options/loadoptions/whitelistedresources/
---
## LoadOptions.WhitelistedResources property

Obtiene o establece fragmentos de direcciones de recursos externos que se cargan incluso cuando [`SkipExternalResources`](../skipexternalresources) es true. El valor predeterminado es una lista vacía.

```csharp
public List<string> WhitelistedResources { get; set; }
```

### Observaciones

Un recurso se carga cuando su dirección completa contiene uno de los fragmentos. La comparación ignora mayúsculas y minúsculas, y los fragmentos vacíos se ignoran. Prefiera fragmentos largos como "https://cdn.example.com/images/": un fragmento corto también coincide con otras direcciones que lo contengan.

Establecer esta propiedad en null borra la lista. La lista no tiene efecto cuando [`SkipExternalResources`](../skipexternalresources) es false, porque entonces se carga cada recurso externo.

### Ver también

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
