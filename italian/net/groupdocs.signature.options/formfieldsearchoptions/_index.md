---
title: "FormFieldSearchOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di ricerca per le firme Formfield."
type: docs
weight: 1590
url: /it/net/groupdocs.signature.options/formfieldsearchoptions/
---
## FormFieldSearchOptions class

Rappresenta le opzioni di ricerca per le firme dei campi modulo.

```csharp
public class FormFieldSearchOptions : SearchOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FormFieldSearchOptions](formfieldsearchoptions)() | Inizializza una nuova istanza della classe FormFieldSearchOptions con valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flag per la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true. |
| [Name](../../groupdocs.signature.options/formfieldsearchoptions/name) { get; set; } | Specifica il modello di espressione regolare del nome della firma del campo modulo se deve essere cercato. È possibile usarlo semplicemente come \"text\" o come espressione regolare tipo \"abc\\d+\". Il valore predefinito è una stringa vuota. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la ricerca. Il valore è opzionale. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine per la ricerca della firma. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Flag per restituire la posizione della forma specificata nel layout del documento. Disponibile solo per documenti Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati. |
| [Type](../../groupdocs.signature.options/formfieldsearchoptions/type) { get; set; } | Specifica il tipo di firma del campo modulo se deve essere cercato. Il valore predefinito è null. |
| [Value](../../groupdocs.signature.options/formfieldsearchoptions/value) { get; set; } | Specifica il valore della firma del campo modulo se deve essere cercato. Il valore predefinito è null. |

### Osservazioni

**Learn more**

* Basic usage of search for FormField electronic signature by GroupDocs.Signature: [How to eSearch FormField signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures)
* Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: [Advanced usage of eSearch FormField signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures)

### Vedi anche

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
