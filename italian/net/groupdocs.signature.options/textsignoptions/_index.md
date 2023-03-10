---
title: TextSignOptions
second_title: Riferimento API GroupDocs.Signature per .NET
description: Rappresenta le opzioni della firma del testo.
type: docs
weight: 1730
url: /it/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

Rappresenta le opzioni della firma del testo.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | Inizializza una nuova istanza della classe TextSignOptions con valori predefiniti. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | Inizializza una nuova istanza della classe TextSignOptions con testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Metti la firma su tutte le pagine del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Ottiene o imposta le impostazioni dello sfondo della firma. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Specifica le impostazioni del bordo |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di documento delle Opzioni firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni firma. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Ottiene o imposta il carattere della firma. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Ottiene o imposta il colore di primo piano della firma. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Ottiene o imposta il titolo del campo del modulo di testo per inserirvi la firma del testo. Questa proprietà può essere utilizzata solo con SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Ottiene o imposta il tipo di campo modulo in cui inserire la firma del testo. Questa proprietà può essere utilizzata solo con SignatureImplementation = TextToFormField. Il valore predefinito è AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Altezza della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) proprietà SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Allineamento orizzontale della firma sulla pagina del documento. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posizione X sinistra della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) Proprietà LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Left e Top. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Ottiene o imposta lo spazio tra i bordi del segno e del documento. (funziona SOLO se è specificato l'allineamento orizzontale o verticale). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Ottiene o imposta l'attributo nativo. Se è impostato, è possibile utilizzare firme specifiche del documento. La filigrana del testo nativo per i documenti di elaborazione di testi è diversa da quella normale, ad esempio. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
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

* Utilizzo di base della creazione di una firma elettronica di testo da parte di GroupDocs.Signature: [Come firmare elettronicamente un documento con la firma di testo](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* Utilizzo avanzato delle impostazioni della firma elettronica di testo con GroupDocs.Signature: [Utilizzo avanzato del documento elettronico con firma di testo e impostazioni aggiuntive](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### Guarda anche

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* spazio dei nomi [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
