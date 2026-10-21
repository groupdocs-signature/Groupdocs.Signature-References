---
title: "DigitalSearchOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di ricerca per le firme digitali."
type: docs
weight: 1550
url: /it/net/groupdocs.signature.options/digitalsearchoptions/
---
## DigitalSearchOptions class

Rappresenta le opzioni di ricerca per le firme digitali.

```csharp
public class DigitalSearchOptions : SearchOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DigitalSearchOptions](digitalsearchoptions)() | Inizializza una nuova istanza della classe DigitalSearchOptions con valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flag per la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true. |
| [Comments](../../groupdocs.signature.options/digitalsearchoptions/comments) { get; set; } | Commenti della firma digitale da cercare. |
| [IssuerName](../../groupdocs.signature.options/digitalsearchoptions/issuername) { get; set; } | Per valori non vuoti specifica il nome distinto dell'emittente del certificato da cercare. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la ricerca. Il valore è opzionale. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine per la ricerca della firma. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Flag per restituire la posizione della forma specificata nel layout del documento. Disponibile solo per documenti Word. |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalsearchoptions/signdatetimefrom) { get; set; } | Intervallo di data e ora della firma digitale da cercare. Il valore nullo verrà ignorato. |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalsearchoptions/signdatetimeto) { get; set; } | Intervallo di data e ora della firma digitale da cercare. Il valore nullo verrà ignorato. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati. |
| [SubjectName](../../groupdocs.signature.options/digitalsearchoptions/subjectname) { get; set; } | Per valori non vuoti specifica il nome distinto del soggetto del certificato da cercare. |

### Osservazioni

**Learn more**

* Basic usage of search for Digital electronic signature by GroupDocs.Signature: [How to eSearch Digital signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
* Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Digital signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

### Vedi anche

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
