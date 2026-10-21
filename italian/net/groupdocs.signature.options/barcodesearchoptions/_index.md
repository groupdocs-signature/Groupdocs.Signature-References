---
title: "BarcodeSearchOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di ricerca per le firme Barcode."
type: docs
weight: 1440
url: /it/net/groupdocs.signature.options/barcodesearchoptions/
---
## BarcodeSearchOptions class

Rappresenta le opzioni di ricerca per le firme Barcode.

```csharp
public class BarcodeSearchOptions : SearchOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BarcodeSearchOptions](barcodesearchoptions#constructor)() | Inizializza una nuova istanza della classe BarcodeSearchOptions con valori predefiniti. |
| [BarcodeSearchOptions](barcodesearchoptions#constructor_1)(BarcodeType) | Inizializza una nuova istanza della classe BarcodeSearchOptions con il valore del tipo di codifica. |
| [BarcodeSearchOptions](barcodesearchoptions#constructor_2)(BarcodeType, string) | Inizializza una nuova istanza della classe BarcodeSearchOptions con i valori del tipo di codifica e del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flag per la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true. |
| [EncodeType](../../groupdocs.signature.options/barcodesearchoptions/encodetype) { get; set; } | Specifica la proprietà Encode Type per cercare i codici a barre. Se questo valore non è impostato, la ricerca viene eseguita per tutti i tipi di codice a barre supportati. |
| [MatchType](../../groupdocs.signature.options/barcodesearchoptions/matchtype) { get; set; } | Ottiene o imposta la ricerca del tipo di corrispondenza del testo Barcode. È usata solo quando la proprietà Text è impostata. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la ricerca. Il valore è opzionale. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine per la ricerca della firma. |
| [ReturnContent](../../groupdocs.signature.options/barcodesearchoptions/returncontent) { get; set; } | Ottiene o imposta il flag per acquisire il contenuto immagine Barcode della firma nella pagina del documento. Se questo flag è impostato su true, il contenuto immagine della firma Barcode manterrà i dati grezzi dell'immagine nel formato richiesto [`ReturnContentType`](./returncontenttype). Per impostazione predefinita questa opzione è disabilitata. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesearchoptions/returncontenttype) { get; set; } | Specifica il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostato a Null. Ciò significa restituire il contenuto immagine del Barcode nel formato originale. Questo formato immagine è specificato in [`Format`](../../groupdocs.signature.domain/barcodesignature/format). I valori supportati possibili sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto immagine del Barcode in formato .png. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Flag per restituire la posizione della forma specificata nel layout del documento. Disponibile solo per documenti Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati. |
| [Text](../../groupdocs.signature.options/barcodesearchoptions/text) { get; set; } | Specifica il testo della firma Barcode se deve essere cercato e corrisposto. |

### Osservazioni

**Learn more**

* Basic usage of search for Barcode electronic signature by GroupDocs.Signature: [How to eSearch Barcode signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures)
* Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures)

### Vedi anche

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
