---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Rappresenta le opzioni della firma immagine."
type: docs
weight: 1670
url: /it/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Rappresenta le opzioni della firma immagine.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Inizializza una nuova istanza della classe ImageSignOptions con valori predefiniti. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Inizializza una nuova istanza della classe ImageSignOptions con lo stream dell'immagine. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Inizializza una nuova istanza della classe ImageSignOptions con il file immagine. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Applica la firma su tutte le pagine del documento. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Specifica le impostazioni del bordo |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di Documento delle Opzioni di Firma [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni della firma. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Ottiene o imposta l'algoritmo di hash da utilizzare per le operazioni crittografiche. Supportato esclusivamente per firme digitali nei file PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Altezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedi [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Allineamento orizzontale della firma sulla pagina del documento. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Ottiene o imposta il percorso del file immagine della firma. Questa proprietà è utilizzata solo se ImageStream non è specificato. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Ottiene o imposta lo stream dell'immagine della firma. Se questa proprietà è specificata, viene sempre usata al posto di ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posizione X sinistra della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedi [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Tipo di misura (pixel, percents or millimeters) per le proprietà Left e Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Ottiene o imposta lo spazio tra la firma e i bordi del documento. (funziona SOLO se l'allineamento orizzontale o verticale è specificato). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rettangolo dell'area in cui posizionare l'immagine sul documento. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angolo di rotazione della firma sulla pagina del documento (in senso orario). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Definisce dove la forma dovrebbe essere presentata nel layout del documento. Disponibile solo per documenti Word. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Ottieni il Tipo di Firma [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Width e Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Modalità di stretching sulla pagina del documento. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Posizione Y superiore della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri, vedi [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento verticale non è specificato). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). Il valore predefinito è 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Allineamento verticale della firma sulla pagina del documento. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Larghezza della Firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ottiene o imposta la posizione Z-order della firma testuale. Determina l'ordine di visualizzazione delle firme sovrapposte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Crea una nuova istanza della classe ImageSignOptions con immagine predefinita da Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Cancella le risorse interne |

### Osservazioni

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Vedi anche

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
