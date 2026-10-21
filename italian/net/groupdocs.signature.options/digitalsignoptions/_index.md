---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni della firma digitale."
type: docs
weight: 1560
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
| [DigitalSignOptions](digitalsignoptions#constructor)() | Inizializza una nuova istanza della classe DigitalSignOptions con i valori predefiniti. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Inizializza una nuova istanza della classe DigitalSignOptions con lo stream del certificato. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Inizializza una nuova istanza della classe DigitalSignOptions con il file del certificato. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Inizializza una nuova istanza della classe DigitalSignOptions con lo stream del certificato e lo stream dell'immagine. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Inizializza una nuova istanza della classe DigitalSignOptions con lo stream del certificato e il file dell'immagine. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Inizializza una nuova istanza della classe DigitalSignOptions con il file del certificato e lo stream dell'immagine. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Inizializza una nuova istanza della classe DigitalSignOptions con il file del certificato e il file dell'immagine. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Ottiene o imposta un flag che consente la firma con un certificato il cui periodo di validità è terminato. Il valore predefinito è false: la firma con un certificato scaduto genera un'eccezione [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), e il documento non viene firmato. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Ottiene o imposta un flag che consente la firma con un certificato il cui periodo di validità non è ancora iniziato. Il valore predefinito è false: la firma con un tale certificato genera un'eccezione [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), e il documento non viene firmato. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Applica la firma su tutte le pagine del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Specifica le impostazioni del bordo |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Ottiene o imposta il percorso del file del certificato digitale. Questa proprietà è utilizzata solo se CertificateStream non è specificato. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Ottiene o imposta lo stream del certificato digitale. Se questa proprietà è specificata, viene sempre utilizzata al posto di CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Ottiene o imposta il contatto della firma. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Ottiene o imposta una funzione di firma hash personalizzata, consentendo agli utenti di implementare la propria logica di firma digitale. Questo permette la firma con certificati esterni e supporta diversi algoritmi hash. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di Documento delle Opzioni di Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni della firma. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Ottiene o imposta l'algoritmo di hash da utilizzare per le operazioni crittografiche. Supportato esclusivamente per firme digitali nei file PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Altezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedi [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Allineamento orizzontale della firma sulla pagina del documento. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Ottiene o imposta il percorso del file immagine della firma. Questa proprietà è utilizzata solo se ImageStream non è specificato. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Ottiene o imposta lo stream dell'immagine della firma. Se questa proprietà è specificata, viene sempre usata al posto di ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posizione X sinistra della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedi [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Ottiene o imposta la posizione della firma. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Tipo di misura (pixel, percents or millimeters) per le proprietà Left e Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Ottiene o imposta lo spazio tra la firma e i bordi del documento. (funziona SOLO se l'allineamento orizzontale o verticale è specificato). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Restituisce o imposta la password del certificato digitale. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Ottiene o imposta il motivo della firma. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rettangolo dell'area in cui posizionare l'immagine sul documento. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angolo di rotazione della firma sulla pagina del documento (in senso orario). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Definisce dove la forma dovrebbe essere presentata nel layout del documento. Disponibile solo per documenti Word. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Ottiene o imposta le proprietà della firma digitale del documento. Per firmare documenti Pdf è possibile impostare proprietà avanzate utilizzando un'istanza di [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Ottieni il Tipo di Firma [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Modalità di stretching sulla pagina del documento. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posizione Y superiore della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedi [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento verticale non è specificato). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). Il valore predefinito è 0 (opaco). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Ottiene/imposta il flag di convalida ltv (Long Term Validation). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Allineamento verticale della firma sulla pagina del documento. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Ottiene o imposta la visibilità della firma. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Larghezza della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | Tipo XAdES [`XAdESType`](./xadestype). Il valore predefinito è None (XAdES è disattivato). Al momento il tipo di firma XAdES è supportato solo per i documenti Spreadsheet. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ottiene o imposta la posizione Z-order della firma testuale. Determina l'ordine di visualizzazione delle firme sovrapposte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Cancella le risorse interne |

### Osservazioni

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Vedi anche

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
