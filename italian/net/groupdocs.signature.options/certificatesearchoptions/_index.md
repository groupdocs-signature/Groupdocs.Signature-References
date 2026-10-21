---
title: "CertificateSearchOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di ricerca per le firme di metadati del certificato."
type: docs
weight: 1490
url: /it/net/groupdocs.signature.options/certificatesearchoptions/
---
## CertificateSearchOptions class

Rappresenta le opzioni di ricerca per le firme di metadati del certificato.

```csharp
public class CertificateSearchOptions : SearchOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CertificateSearchOptions](certificatesearchoptions#constructor)() | Inizializza una nuova istanza della classe TextSearchOptions con i valori predefiniti. |
| [CertificateSearchOptions](certificatesearchoptions#constructor_1)(string) | Inizializza una nuova istanza della classe TextSearchOptions con il valore di testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flag per la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true. |
| [MatchType](../../groupdocs.signature.options/certificatesearchoptions/matchtype) { get; set; } | Ottiene o imposta il tipo di ricerca di corrispondenza del testo. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la ricerca. Il valore è opzionale. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine per la ricerca della firma. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Flag per restituire la posizione della forma specificata nel layout del documento. Disponibile solo per documenti Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati. |
| [Text](../../groupdocs.signature.options/certificatesearchoptions/text) { get; set; } | Specifica il testo della proprietà del certificato da confrontare durante la ricerca. |

### Osservazioni

**Learn more**

* Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: [Advanced search within Digital Certificate X509 documents](https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

### Vedi anche

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
