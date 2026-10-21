---
title: "SearchOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa las opciones para extraer firmas del documento."
type: docs
weight: 1960
url: /es/net/groupdocs.signature.options/searchoptions/
---
## SearchOptions class

Representa las opciones para extraer firmas del documento.

```csharp
public abstract class SearchOptions
```

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicador para buscar en cada página del documento. Por defecto, este valor está establecido en true. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la búsqueda. El valor es opcional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opciones para especificar páginas para la búsqueda de firmas. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Indicador para devolver la posición de la forma especificada en el diseño del documento. Disponible solo para documentos Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicador para devolver solo las firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados. |

### Observaciones

**Learn more**

* See more simple examples on searching for various electronic signatures with GroupDocs.Signature: [https://docs.groupdocs.com/signature/net/search-for-electronic-signatures-in-document/](https://docs.groupdocs.com/signature/net/search-for-electronic-signatures-in-document/)
* See more advanced examples of searching for various electronic signature with GroupDocs.Signature: [Advanced electronic signatures search](https://docs.groupdocs.com/signature/net/searching/)

### Ver también

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
