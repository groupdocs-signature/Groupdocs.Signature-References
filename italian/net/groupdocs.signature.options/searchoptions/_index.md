---
title: "SearchOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di estrazione delle firme dal documento."
type: docs
weight: 1960
url: /it/net/groupdocs.signature.options/searchoptions/
---
## SearchOptions class

Rappresenta le opzioni di estrazione delle firme dal documento.

```csharp
public abstract class SearchOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flag per la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la ricerca. Il valore è opzionale. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine per la ricerca della firma. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Flag per restituire la posizione della forma specificata nel layout del documento. Disponibile solo per documenti Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati. |

### Osservazioni

**Learn more**

* See more simple examples on searching for various electronic signatures with GroupDocs.Signature: [https://docs.groupdocs.com/signature/net/search-for-electronic-signatures-in-document/](https://docs.groupdocs.com/signature/net/search-for-electronic-signatures-in-document/)
* See more advanced examples of searching for various electronic signature with GroupDocs.Signature: [Advanced electronic signatures search](https://docs.groupdocs.com/signature/net/searching/)

### Vedi anche

* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
