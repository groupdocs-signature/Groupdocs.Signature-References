---
title: ImageSignOptions
second_title: Riferimento API GroupDocs.Signature per .NET
description: Rappresenta le opzioni della firma dellimmagine.
type: docs
weight: 1420
url: /it/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Rappresenta le opzioni della firma dell'immagine.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Inizializza una nuova istanza della classe ImageSignOptions con valori predefiniti. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Inizializza una nuova istanza della classe ImageSignOptions con flusso di immagini. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Inizializza una nuova istanza della classe ImageSignOptions con file immagine. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Metti la firma su tutte le pagine del documento. Questa proprietà può essere utilizzata solo per i formati immagine multi-frame (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Specifica le impostazioni del bordo |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di documento delle Opzioni firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni firma. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Altezza della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) DimensioneMisuraTipo). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Allineamento orizzontale della firma sulla pagina del documento. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Ottiene o imposta il percorso del file dell'immagine della firma. Questa proprietà viene utilizzata solo se ImageStream non è specificato. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Ottiene o imposta il flusso dell'immagine della firma. Se questa proprietà è specificata, viene sempre utilizzata al suo posto ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posizione X sinistra della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Left e Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Ottiene o imposta lo spazio tra i bordi del segno e del documento. (funziona SOLO se è specificato l'allineamento orizzontale o verticale). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rettangolo dell'area in cui posizionare l'immagine sul documento. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angolo di rotazione della firma sulla pagina del documento (in senso orario). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Ottieni il tipo di firma[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Larghezza e Altezza. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Modalità di stiramento sulla pagina del documento. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Posizione della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento verticale non è specificato). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Ottiene o imposta la trasparenza della firma (valore compreso tra 0,0 (opaco) e 1,0 (chiaro)). Il valore predefinito è 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Allineamento verticale della firma sulla pagina del documento. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri[`MeasureType`](../../groupdocs.signature.domain/measuretype) DimensioneMisuraTipo). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ottiene o imposta la posizione dell'ordine Z della segnatura del testo. Determina l'ordine di visualizzazione delle segnature sovrapposte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Crea una nuova istanza della classe ImageSignOptions con immagine predefinita da Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Cancella le risorse interne |

### Osservazioni

**Saperne di più**

* Utilizzo di base della creazione della firma elettronica dell'immagine da parte di GroupDocs.Signature: [Come firmare un documento elettronico con la firma dell'immagine](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Utilizzo avanzato delle impostazioni della firma elettronica dell'immagine con GroupDocs.Signature: [Utilizzo avanzato per firmare elettronicamente il documento con la firma dell'immagine e impostazioni aggiuntive](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Guarda anche

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* spazio dei nomi [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
