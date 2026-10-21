---
title: "CertificateSearchOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones de búsqueda para firmas de metadatos de certificado."
type: docs
weight: 1490
url: /es/net/groupdocs.signature.options/certificatesearchoptions/
---
## CertificateSearchOptions class

Representa opciones de búsqueda para firmas de metadatos de certificado.

```csharp
public class CertificateSearchOptions : SearchOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CertificateSearchOptions](certificatesearchoptions#constructor)() | Inicializa una nueva instancia de la clase TextSearchOptions con valores predeterminados. |
| [CertificateSearchOptions](certificatesearchoptions#constructor_1)(string) | Inicializa una nueva instancia de la clase TextSearchOptions con un valor de texto. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicador para buscar en cada página del documento. Por defecto, este valor está establecido en true. |
| [MatchType](../../groupdocs.signature.options/certificatesearchoptions/matchtype) { get; set; } | Obtiene o establece la búsqueda del tipo de coincidencia de texto. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la búsqueda. El valor es opcional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opciones para especificar páginas para la búsqueda de firmas. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Indicador para devolver la posición de la forma especificada en el diseño del documento. Disponible solo para documentos Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicador para devolver solo las firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados. |
| [Text](../../groupdocs.signature.options/certificatesearchoptions/text) { get; set; } | Especifica el texto de la propiedad del certificado para coincidir en la búsqueda. |

### Observaciones

**Learn more**

* Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: [Advanced search within Digital Certificate X509 documents](https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

### Ver también

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
