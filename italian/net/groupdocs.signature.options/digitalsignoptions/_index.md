---
title: DigitalSignOptions
second_title: Riferimento API GroupDocs.Signature per .NET
description: Rappresenta le opzioni della firma digitale.
type: docs
weight: 1340
url: /it/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Rappresenta le opzioni della firma digitale.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Inizializza una nuova istanza della classe DigitalSignOptions con valori predefiniti. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Inizializza una nuova istanza della classe DigitalSignOptions con flusso di certificato. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Inizializza una nuova istanza della classe DigitalSignOptions con file di certificato. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Inizializza una nuova istanza della classe DigitalSignOptions con flusso di certificati e flusso di immagini. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Inizializza una nuova istanza della classe DigitalSignOptions con flusso di certificato e file immagine. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Inizializza una nuova istanza della classe DigitalSignOptions con file di certificato e flusso di immagini. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Inizializza una nuova istanza della classe DigitalSignOptions con file di certificato e file immagine. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Metti la firma su tutte le pagine del documento. Questa proprietà può essere utilizzata solo per i formati immagine multi-frame (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Specifica le impostazioni del bordo |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Ottiene o imposta il percorso del file del certificato digitale. Questa proprietà viene utilizzata solo se CertificateStream non è specificato. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Ottiene o imposta il flusso del certificato digitale. Se questa proprietà è specificata, viene sempre utilizzata al suo posto CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Ottiene o imposta il contatto della firma. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di documento delle Opzioni firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni firma. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Altezza della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) DimensioneMisuraTipo). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Allineamento orizzontale della firma sulla pagina del documento. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Ottiene o imposta il percorso del file dell'immagine della firma. Questa proprietà viene utilizzata solo se ImageStream non è specificato. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Ottiene o imposta il flusso dell'immagine della firma. Se questa proprietà è specificata, viene sempre utilizzata al suo posto ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posizione X sinistra della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Ottiene o imposta la posizione della firma. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Left e Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Ottiene o imposta lo spazio tra i bordi del segno e del documento. (funziona SOLO se è specificato l'allineamento orizzontale o verticale). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Ottiene o imposta la password del certificato digitale. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Ottiene o imposta il motivo della firma. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rettangolo dell'area in cui posizionare l'immagine sul documento. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angolo di rotazione della firma sulla pagina del documento (in senso orario). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Ottiene o imposta le proprietà della firma digitale del documento. Per la firma di documenti Pdf è possibile impostare proprietà avanzate utilizzando l'istanza di[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Ottieni il tipo di firma[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Larghezza e Altezza. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Modalità di stiramento sulla pagina del documento. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Posizione della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento verticale non è specificato). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Ottiene o imposta la trasparenza della firma (valore compreso tra 0,0 (opaco) e 1,0 (chiaro)). Il valore predefinito è 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Allineamento verticale della firma sulla pagina del documento. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Ottiene o imposta la visibilità della firma. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri[`MeasureType`](../../groupdocs.signature.domain/measuretype) DimensioneMisuraTipo). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | Tipo XAdES[`XAdESType`](./xadestype) . Il valore predefinito è Nessuno (XAdES è disattivato). Al momento il tipo di firma XAdES è supportato solo per i documenti Spreadsheet. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ottiene o imposta la posizione dell'ordine Z della segnatura del testo. Determina l'ordine di visualizzazione delle segnature sovrapposte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Cancella le risorse interne |

### Osservazioni

**Saperne di più**

* Utilizzo di base della creazione di una firma elettronica digitale da parte di GroupDocs.Signature: [Come firmare un documento elettronico con la firma digitale](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Utilizzo avanzato delle impostazioni della firma elettronica digitale con GroupDocs.Signature: [Utilizzo avanzato del documento elettronico con firma digitale e impostazioni aggiuntive](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Guarda anche

* class [ImageSignOptions](../imagesignoptions)
* spazio dei nomi [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
