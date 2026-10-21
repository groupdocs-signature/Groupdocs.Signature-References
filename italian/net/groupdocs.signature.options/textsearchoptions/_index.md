---
title: "TextSearchOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di ricerca per le firme Text."
type: docs
weight: 2010
url: /it/net/groupdocs.signature.options/textsearchoptions/
---
## TextSearchOptions class

Rappresenta le opzioni di ricerca per le firme Text.

```csharp
public class TextSearchOptions : SearchOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextSearchOptions](textsearchoptions#constructor)() | Inizializza una nuova istanza della classe TextSearchOptions con i valori predefiniti. |
| [TextSearchOptions](textsearchoptions#constructor_1)(string) | Inizializza una nuova istanza della classe TextSearchOptions con il valore di testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flag per la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true. |
| [MatchType](../../groupdocs.signature.options/textsearchoptions/matchtype) { get; set; } | Ottiene o imposta il tipo di ricerca di corrispondenza del testo. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la ricerca. Il valore è opzionale. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine per la ricerca della firma. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Flag per restituire la posizione della forma specificata nel layout del documento. Disponibile solo per documenti Word. |
| [SignatureImplementation](../../groupdocs.signature.options/textsearchoptions/signatureimplementation) { get; set; } | Specifica l'implementazione della firma di testo da cercare. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati. |
| [Text](../../groupdocs.signature.options/textsearchoptions/text) { get; set; } | Specifica il testo della firma da far corrispondere durante la ricerca. |

### Osservazioni

**Learn more**

* Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
* Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

### Vedi anche

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
