---
title: "DigitalSearchOptions"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "Representa opciones de búsqueda para firmas digitales."
type: docs
weight: 1550
url: /es/net/groupdocs.signature.options/digitalsearchoptions/
---
## DigitalSearchOptions class

Representa opciones de búsqueda para firmas digitales.

```csharp
public class DigitalSearchOptions : SearchOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DigitalSearchOptions](digitalsearchoptions)() | Inicializa una nueva instancia de la clase DigitalSearchOptions con valores predeterminados. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Indicador para buscar en cada página del documento. Por defecto, este valor está establecido en true. |
| [Comments](../../groupdocs.signature.options/digitalsearchoptions/comments) { get; set; } | Comentarios de la firma digital a buscar. |
| [IssuerName](../../groupdocs.signature.options/digitalsearchoptions/issuername) { get; set; } | Para valores no vacíos especifica el nombre distinguido del emisor del certificado a buscar. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Obtiene o establece el número de página del documento para la búsqueda. El valor es opcional. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opciones para especificar páginas para la búsqueda de firmas. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Indicador para devolver la posición de la forma especificada en el diseño del documento. Disponible solo para documentos Word. |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalsearchoptions/signdatetimefrom) { get; set; } | Rango de fecha y hora de la firma digital a buscar. Los valores nulos se ignorarán. |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalsearchoptions/signdatetimeto) { get; set; } | Rango de fecha y hora de la firma digital a buscar. Los valores nulos se ignorarán. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Indicador para devolver solo las firmas marcadas como IsSignature. Por defecto, el valor es false, lo que indica que se devolverán todas las firmas que coincidan con los criterios especificados. |
| [SubjectName](../../groupdocs.signature.options/digitalsearchoptions/subjectname) { get; set; } | Para valores no vacíos especifica el nombre distinguido del sujeto del certificado a buscar. |

### Observaciones

**Learn more**

* Basic usage of search for Digital electronic signature by GroupDocs.Signature: [How to eSearch Digital signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
* Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Digital signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

### Ver también

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
