---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni di ricerca per le firme QRCode."
type: docs
weight: 1910
url: /it/net/groupdocs.signature.options/qrcodesearchoptions/
---
## QrCodeSearchOptions class

Rappresenta le opzioni di ricerca per le firme QR-Code.

```csharp
public class QrCodeSearchOptions : SearchOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [QrCodeSearchOptions](qrcodesearchoptions#constructor)() | Inizializza una nuova istanza della classe QRCodeSearchOptions con i valori predefiniti. |
| [QrCodeSearchOptions](qrcodesearchoptions#constructor_1)(QrCodeType) | Inizializza una nuova istanza della classe QRCodeSearchOptions con il valore del tipo di codifica. |
| [QrCodeSearchOptions](qrcodesearchoptions#constructor_2)(QrCodeType, string) | Inizializza una nuova istanza della classe QRCodeSearchOptions con i valori del tipo di codifica e del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | Flag per la ricerca su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesearchoptions/dataencryption) { get; set; } | Ottiene o imposta l'implementazione dell'interfaccia [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
| [EncodeType](../../groupdocs.signature.options/qrcodesearchoptions/encodetype) { get; set; } | Specifica la proprietà Tipo di Codifica per cercare i QR-Code. Se questo valore non è impostato, la ricerca viene eseguita per tutti i tipi di QR-Code supportati. |
| [MatchType](../../groupdocs.signature.options/qrcodesearchoptions/matchtype) { get; set; } | Ottiene o imposta la ricerca del Tipo di Corrispondenza del Testo QR-Code. Viene usata solo quando la proprietà Testo è impostata. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la ricerca. Il valore è opzionale. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine per la ricerca della firma. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesearchoptions/returncontent) { get; set; } | Ottiene o imposta il flag per acquisire il contenuto immagine QR-Code della firma nella pagina del documento. Se questo flag è impostato su true, il contenuto immagine della firma QR-Code manterrà i dati immagine grezzi nel formato richiesto [`ReturnContentType`](./returncontenttype). Per impostazione predefinita questa opzione è disabilitata. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesearchoptions/returncontenttype) { get; set; } | Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostato a Null. Ciò significa restituire il contenuto immagine QR-Code nel formato originale. Questo formato immagine è specificato in [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto immagine QR-Code in .png originale. |
| [ShapePosition](../../groupdocs.signature.options/searchoptions/shapeposition) { get; set; } | Flag per restituire la posizione della forma specificata nel layout del documento. Disponibile solo per documenti Word. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati. |
| [Text](../../groupdocs.signature.options/qrcodesearchoptions/text) { get; set; } | Specifica il Testo della firma QR-Code se deve essere cercato e corrisposto. |

### Osservazioni

**Learn more**

* Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: [How to eSearch QR-Code signatures in a document ](https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
* Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: [Advanced usage of eSearch QR-Code signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

### Vedi anche

* class [SearchOptions](../searchoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
