---
title: QrCodeSignOptions
second_title: Riferimento API GroupDocs.Signature per .NET
description: Rappresenta le opzioni di firma del codice QR.
type: docs
weight: 1630
url: /it/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Rappresenta le opzioni di firma del codice QR.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Inizializza una nuova istanza della classe QRCodeSignOptions con valori predefiniti. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Inizializza una nuova istanza della classe QRCodeSignOptions con testo. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Inizializza una nuova istanza della classe BarcodeSignOptions con testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Metti la firma su tutte le pagine del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Ottiene o imposta le impostazioni dello sfondo della firma. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Specifica le impostazioni del bordo |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Ottiene o imposta l'allineamento del testo nell'immagine del codice QR del risultato. Il valore predefinito è Nessuno. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Ottiene o imposta l'oggetto personalizzato da serializzare nel contenuto del codice QR. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Ottiene o imposta l'implementazione di[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interfaccia per codificare e decodificare le proprietà del testo della firma del codice QR o dei dati. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di documento delle Opzioni firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Ottiene o imposta il tipo di codice QR. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni firma. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Ottiene o imposta il carattere della firma. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Ottiene o imposta il colore Fore delle barre del QR-Code L'utilizzo di questa proprietà potrebbe causare problemi con la verifica. Usalo con attenzione. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Ottiene o imposta il titolo del campo del modulo di testo per inserirvi la firma del testo. Questa proprietà può essere utilizzata solo con SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Ottiene o imposta il tipo di campo modulo in cui inserire la firma del testo. Questa proprietà può essere utilizzata solo con SignatureImplementation = TextToFormField. Il valore predefinito è AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Altezza della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) proprietà SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Allineamento orizzontale della firma sulla pagina del documento. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Ottiene o imposta lo spazio tra gli elementi del codice QR e i bordi dell'immagine del risultato. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posizione X sinistra della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) Proprietà LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Left e Top. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Ottiene o imposta il nome del file dell'immagine del logo del codice QR. Questa proprietà è utilizzata solo se LogoStream non è specificato. L'utilizzo di questa proprietà potrebbe causare problemi con la verifica. Usalo con attenzione. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Ottiene o imposta il flusso dell'immagine del logo del codice QR. Se questa proprietà è specificata, viene sempre utilizzata invece LogoFilePath. L'utilizzo di questa proprietà potrebbe causare problemi con la verifica. Usalo con attenzione. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Ottiene o imposta lo spazio tra i bordi del segno e del documento. (funziona SOLO se è specificato l'allineamento orizzontale o verticale). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Ottiene o imposta l'attributo nativo. Se è impostato, è possibile utilizzare firme specifiche del documento. La filigrana del testo nativo per i documenti di elaborazione di testi è diversa da quella normale, ad esempio. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Ottiene o imposta il flag per ottenere il contenuto dell'immagine del codice QR di una firma che è stata inserita nella pagina del documento. Se questo flag è impostato su true, il contenuto dell'immagine della firma del codice QR manterrà i dati dell'immagine non elaborata nel formato richiesto[`ReturnContentType`](./returncontenttype) . Per impostazione predefinita questa opzione è disabilitata. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Specifica il tipo di file del contenuto dell'immagine restituita della firma del codice QR quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostata su Null. Ciò significa restituire il contenuto dell'immagine QR-Code nel formato originale. Questo formato immagine è specificato in[`Format`](../../groupdocs.signature.domain/qrcodesignature/format) I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto dell'immagine del codice QR in formato .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Angolo di rotazione della firma sulla pagina del documento (in senso orario). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Ottiene o imposta il tipo di forma in cui inserire il testo. Questa proprietà può essere utilizzata solo con SignatureImplementation = TextStamp. Il valore predefinito è Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Ottiene o imposta l'ID univoco della firma. Può essere utilizzato nelle opzioni di verifica della firma. La proprietà è supportata solo per i documenti Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Ottiene o imposta il tipo di implementazione della firma di testo. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Ottieni il tipo di firma[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Larghezza e Altezza. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Modalità di stiramento sulla pagina del documento. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Ottiene o imposta il testo della firma. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Allineamento orizzontale del testo all'interno di una firma. Questa funzione è supportata solo per le implementazioni della firma di immagini e annotazioni (vedere[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) Proprietà SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Allineamento verticale del testo all'interno di una firma. Questa funzione è supportata solo per l'implementazione della firma immagine (vedere[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) Proprietà SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Top Y Posizione della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype)Proprietà LocationMeasureType). (funziona se l'allineamento verticale non è specificato). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Ottiene o imposta la trasparenza della firma (valore compreso tra 0,0 (opaco) e 1,0 (chiaro)). Il valore predefinito è 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Allineamento verticale della firma sulla pagina del documento. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) proprietà SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ottiene o imposta la posizione dell'ordine Z della segnatura del testo. Determina l'ordine di visualizzazione delle segnature sovrapposte. |

### Osservazioni

**Saperne di più**

* Utilizzo di base della creazione della firma elettronica del codice QR da parte di GroupDocs.Firma: [Come firmare un documento elettronico con la firma del codice QR](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Utilizzo avanzato delle impostazioni della firma elettronica QR-Code con GroupDocs.Firma: [Utilizzo avanzato per firmare elettronicamente il documento con la firma del codice QR e impostazioni aggiuntive](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### Guarda anche

* class [TextSignOptions](../textsignoptions)
* spazio dei nomi [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
