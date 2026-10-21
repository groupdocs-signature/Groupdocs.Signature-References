---
title: "ImageSearchOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di ricerca per le firme immagine."
type: docs
weight: 1660
url: /it/net/groupdocs.signature.options/imagesearchoptions/
---
## ImageSearchOptions class

Rappresenta le opzioni di ricerca per le firme immagine.

```csharp
public class ImageSearchOptions : SearchOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageSearchOptions](imagesearchoptions)() | Inizializza una nuova istanza della classe ImageSearchOptions con i valori predefiniti. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flag per la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true. |
| [MaxContentSize](../../groupdocs.signature.options/imagesearchoptions/maxcontentsize) { get; set; } | Per valore diverso da zero, questo flag specifica la dimensione massima delle immagini per i criteri di ricerca. Per impostazione predefinita questo flag è impostato a zero e non influisce sul risultato della ricerca. |
| [MinContentSize](../../groupdocs.signature.options/imagesearchoptions/mincontentsize) { get; set; } | Per valore diverso da zero, questo flag specifica la dimensione minima delle immagini per i criteri di ricerca. Per impostazione predefinita questo flag è impostato a zero e non influisce sul risultato della ricerca. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la ricerca. Il valore è opzionale. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine per la ricerca della firma. |
| [ReturnContent](../../groupdocs.signature.options/imagesearchoptions/returncontent) { get; set; } | Ottiene o imposta il flag per acquisire il contenuto immagine della firma nella pagina del documento. Se questo flag è impostato su true, il contenuto dell'immagine della firma manterrà i dati immagine grezzi nel formato richiesto [`ReturnContentType`](./returncontenttype). Per impostazione predefinita questa opzione è disabilitata. |
| [ReturnContentType](../../groupdocs.signature.options/imagesearchoptions/returncontenttype) { get; set; } | Specifica il tipo di file del contenuto restituito della firma immagine quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostato a Null. Ciò significa restituire il contenuto dell'immagine nel formato originale. Questo formato immagine è specificato in [`Format`](../../groupdocs.signature.domain/imagesignature/format). I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto dell'immagine nel formato originale. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Flag per restituire la posizione della forma specificata nel layout del documento. Disponibile solo per documenti Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati. |

### Osservazioni

**Learn more**

* Basic usage of search for Image electronic signature by GroupDocs.Signature: [How to eSearch Image signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures)
* Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Image signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures)

### Vedi anche

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
