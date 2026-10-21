---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni della firma QRCode."
type: docs
weight: 1920
url: /it/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Rappresenta le opzioni della firma QR-Code.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Inizializza una nuova istanza della classe QRCodeSignOptions con i valori predefiniti. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Inizializza una nuova istanza della classe QRCodeSignOptions con il testo. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Inizializza una nuova istanza della classe BarcodeSignOptions con testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Applica la firma su tutte le pagine del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Ottiene o imposta le impostazioni dello sfondo della firma. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Specifica le impostazioni del bordo |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Ottiene o imposta l'allineamento del testo nell'immagine QR-code risultante. Il valore predefinito è None. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Ottiene o imposta l'oggetto personalizzato da serializzare nel contenuto QR-Code. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Ottiene o imposta l'implementazione dell'interfaccia [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di Documento delle Opzioni di Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Ottiene o imposta il tipo di QR-Code. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni della firma. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Ottiene o imposta il carattere della firma. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Ottiene o imposta il colore di primo piano delle barre QR-Code. L'uso di questa proprietà potrebbe causare problemi con la verifica. Usala con attenzione. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Ottiene o imposta il titolo del campo modulo di testo in cui inserire la firma testuale. Questa proprietà può essere usata solo con SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Ottiene o imposta il tipo di campo modulo in cui inserire la firma testuale. Questa proprietà può essere usata solo con SignatureImplementation = TextToFormField. Il valore predefinito è AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Ottiene o imposta l'algoritmo di hash da utilizzare per le operazioni crittografiche. Supportato esclusivamente per firme digitali nei file PDF. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Altezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedi la proprietà [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Allineamento orizzontale della firma sulla pagina del documento. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Ottiene o imposta lo spazio tra gli elementi QR-Code e i bordi dell'immagine risultante. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posizione X sinistra della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere [`MeasureType`](../../groupdocs.signature.domain/measuretype) proprietà LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Tipo di misura (pixel, percents or millimeters) per le proprietà Left e Top. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Ottiene o imposta il nome file dell'immagine del logo QR-code. Questa proprietà è utilizzata solo se LogoStream non è specificato. L'uso di questa proprietà potrebbe causare problemi con la verifica. Usala con attenzione. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Ottiene o imposta lo stream dell'immagine del logo QR-code. Se questa proprietà è specificata, viene sempre usata al posto di LogoFilePath. L'uso di questa proprietà potrebbe causare problemi con la verifica. Usala con attenzione. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Ottiene o imposta lo spazio tra la firma e i bordi del documento. (funziona SOLO se l'allineamento orizzontale o verticale è specificato). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Ottiene o imposta l'attributo nativo. Se impostato, è possibile utilizzare firme specifiche del documento. La filigrana di testo nativa per i documenti WordProcessing è diversa da quella regolare, ad esempio. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Ottiene o imposta il flag per ottenere il contenuto immagine QR-Code di una firma inserita nella pagina del documento. Se questo flag è impostato su true, il contenuto immagine della firma QR-Code manterrà i dati grezzi dell'immagine nel formato richiesto [`ReturnContentType`](./returncontenttype). Per impostazione predefinita questa opzione è disabilitata. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Specifica il tipo di file del contenuto immagine restituito della firma QR-Code quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostata a Null. Ciò significa restituire il contenuto immagine QR-Code nel formato originale. Questo formato immagine è specificato in [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto immagine QR-Code in formato .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Angolo di rotazione della firma sulla pagina del documento (in senso orario). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Definisce dove la forma dovrebbe essere presentata nel layout del documento. Disponibile solo per documenti Word. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Ottiene o imposta il tipo di forma per inserire il testo. Questa proprietà può essere usata solo con SignatureImplementation = TextStamp. Il valore predefinito è Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Ottiene o imposta l'ID univoco della firma. Può essere utilizzato nelle opzioni di verifica della firma. La proprietà è supportata solo per i documenti Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Ottiene o imposta il tipo di implementazione della firma di testo. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Ottieni il Tipo di Firma [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Modalità di stretching sulla pagina del documento. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Ottiene o imposta il testo della firma. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Allineamento orizzontale del testo all'interno di una firma. Questa funzionalità è supportata solo per le implementazioni di firma Image e Annotation (vedi [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) proprietà SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Allineamento verticale del testo all'interno di una firma. Questa funzionalità è supportata solo per l'implementazione di firma Image (vedi [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) proprietà SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Posizione Y superiore della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere [`MeasureType`](../../groupdocs.signature.domain/measuretype) proprietà LocationMeasureType). (funziona se l'allineamento verticale non è specificato). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). Il valore predefinito è 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Allineamento verticale della firma sulla pagina del documento. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere [`MeasureType`](../../groupdocs.signature.domain/measuretype) proprietà SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ottiene o imposta la posizione Z-order della firma testuale. Determina l'ordine di visualizzazione delle firme sovrapposte. |

### Osservazioni

**Learn more**

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Vedi anche

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
