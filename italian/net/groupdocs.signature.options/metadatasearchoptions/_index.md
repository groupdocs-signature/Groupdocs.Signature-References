---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di ricerca per le firme Metadata."
type: docs
weight: 1730
url: /it/net/groupdocs.signature.options/metadatasearchoptions/
---
## MetadataSearchOptions class

Rappresenta le opzioni di ricerca per le firme Metadata.

```csharp
public class MetadataSearchOptions : SearchOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MetadataSearchOptions](metadatasearchoptions)() | Inizializza una nuova istanza della classe MetadataSearchOptions con valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flag per la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true. |
| [DataEncryption](../../groupdocs.signature.options/metadatasearchoptions/dataencryption) { get; set; } | Ottiene o imposta l'implementazione dell'interfaccia [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) per decrittare tutte le firme Metadata all'interno di questa raccolta di opzioni. Se questo valore è impostato, tutte le firme trovate utilizzeranno questa crittografia per impostazione predefinita o la propria DataEncryption se è stata assegnata. |
| [IncludeBuiltinProperties](../../groupdocs.signature.options/metadatasearchoptions/includebuiltinproperties) { get; set; } | Indica se le proprietà di documento integrate, come statistiche del documento, informazioni, ecc., devono essere incluse nei risultati di ricerca. Questa opzione ha senso per i tipi di file di presentazione, foglio di calcolo e elaborazione testi. |
| [Name](../../groupdocs.signature.options/metadatasearchoptions/name) { get; set; } | Specifica il nome della firma dei metadati se deve essere cercato e corrisposto. |
| [NameMatchType](../../groupdocs.signature.options/metadatasearchoptions/namematchtype) { get; set; } | Ottiene o imposta il tipo di corrispondenza del nome dei metadati nella ricerca. Viene usato solo quando la proprietà Name è impostata. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la ricerca. Il valore è opzionale. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine per la ricerca della firma. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Flag per restituire la posizione della forma specificata nel layout del documento. Disponibile solo per documenti Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati. |

### Osservazioni

**Learn more**

* Basic usage of search for Metadata electronic signature by GroupDocs.Signature: [How to eSearch Metadata signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures)
* Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Metadata signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures)

### Vedi anche

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
