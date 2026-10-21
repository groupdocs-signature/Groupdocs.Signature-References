---
title: "TextSearchOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones de búsqueda para firmas de texto."
type: docs
weight: 2010
url: /es/net/groupdocs.signature.options/textsearchoptions/
---
## TextSearchOptions class

Representa opciones de búsqueda para firmas de texto.

```csharp
public class TextSearchOptions : SearchOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextSearchOptions](textsearchoptions#constructor)() | Inicializa una nueva instancia de la clase TextSearchOptions con valores predeterminados. |
| [TextSearchOptions](textsearchoptions#constructor_1)(string) | Inicializa una nueva instancia de la clase TextSearchOptions con un valor de texto. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicador para buscar en cada página del documento. Por defecto, este valor está establecido en true. |
| [MatchType](../../groupdocs.signature.options/textsearchoptions/matchtype) { get; set; } | Obtiene o establece la búsqueda del tipo de coincidencia de texto. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la búsqueda. El valor es opcional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opciones para especificar páginas para la búsqueda de firmas. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Indicador para devolver la posición de la forma especificada en el diseño del documento. Disponible solo para documentos Word. |
| [SignatureImplementation](../../groupdocs.signature.options/textsearchoptions/signatureimplementation) { get; set; } | Especifica la implementación de firma de texto para buscar. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicador para devolver solo las firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados. |
| [Text](../../groupdocs.signature.options/textsearchoptions/text) { get; set; } | Especifica el texto de la firma para coincidir durante la búsqueda. |

### Observaciones

**Learn more**

* Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
* Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

### Ver también

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
