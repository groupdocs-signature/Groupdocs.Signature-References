---
title: "TextSignOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni della firma Text."
type: docs
weight: 2020
url: /it/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

Rappresenta le opzioni della firma Text.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | Inizializza una nuova istanza della classe TextSignOptions con i valori predefiniti. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | Inizializza una nuova istanza della classe TextSignOptions con il testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Applica la firma su tutte le pagine del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Ottiene o imposta le impostazioni dello sfondo della firma. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Specifica le impostazioni del bordo |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di Documento delle Opzioni di Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni della firma. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Ottiene o imposta il carattere della firma. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Ottiene o imposta il colore di primo piano della firma. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Ottiene o imposta il titolo del campo modulo di testo in cui inserire la firma testuale. Questa proprietà può essere usata solo con SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Ottiene o imposta il tipo di campo modulo in cui inserire la firma testuale. Questa proprietà può essere usata solo con SignatureImplementation = TextToFormField. Il valore predefinito è AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Ottiene o imposta l'algoritmo di hash da utilizzare per le operazioni crittografiche. Supportato esclusivamente per firme digitali nei file PDF. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Altezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedi la proprietà [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Allineamento orizzontale della firma sulla pagina del documento. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Posizione X sinistra della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedere [`MeasureType`](../../groupdocs.signature.domain/measuretype) proprietà LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Tipo di misura (pixel, percents or millimeters) per le proprietà Left e Top. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Ottiene o imposta lo spazio tra la firma e i bordi del documento. (funziona SOLO se l'allineamento orizzontale o verticale è specificato). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Ottiene o imposta l'attributo nativo. Se impostato, è possibile utilizzare firme specifiche del documento. La filigrana di testo nativa per i documenti WordProcessing è diversa da quella regolare, ad esempio. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
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

* Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### Vedi anche

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
