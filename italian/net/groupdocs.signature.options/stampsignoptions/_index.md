---
title: StampSignOptions
second_title: Riferimento API GroupDocs.Signature per .NET
description: Rappresenta le opzioni della firma del timbro.
type: docs
weight: 1630
url: /it/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Rappresenta le opzioni della firma del timbro.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Inizializza una nuova istanza della classe StampSignOptions con valori predefiniti. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Inizializza una nuova istanza della classe StampSignOptions con opzioni di allineamento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Metti la firma su tutte le pagine del documento. Questa proprietà può essere utilizzata solo per i formati immagine multi-frame (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Aspetto aggiuntivo della firma. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Ottiene o imposta lo sfondo del timbro. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Ottiene o imposta il tipo di ritaglio del colore di sfondo della firma. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Ottiene o imposta il tipo di ritaglio dell'immagine di sfondo della firma. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Specifica le impostazioni del bordo |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Ottieni o imposta il Tipo di documento delle Opzioni firma[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Estensioni firma. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Altezza della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Allineamento orizzontale della firma sulla pagina del documento. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Ottiene o imposta il percorso del file dell'immagine della firma. Questa proprietà viene utilizzata solo se ImageStream non è specificato. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Ottiene o imposta il flusso dell'immagine della firma. Se questa proprietà è specificata, viene sempre utilizzata al suo posto ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Elenco di linee interne renderizzate come un insieme di rettangoli. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Posizione X sinistra della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento orizzontale non è specificato). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Left e Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Ottiene o imposta lo spazio tra i bordi del segno e del documento. (funziona SOLO se è specificato l'allineamento orizzontale o verticale). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per Margin. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Elenco delle linee esterne rese come cerchi concentrici. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina del documento per la firma. Il valore minimo e predefinito è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Opzioni per specificare le pagine da firmare. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rettangolo dell'area in cui posizionare l'immagine sul documento. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Angolo di rotazione della firma sulla pagina del documento (in senso orario). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Ottieni il tipo di firma[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Larghezza e Altezza. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Ottiene o imposta il tipo di timbro. Il valore predefinito è Round. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Modalità di stiramento sulla pagina del documento. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Posizione della firma sulla pagina del documento nei valori di misura (pixel, percentuali o millimetri vedere[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (funziona se l'allineamento verticale non è specificato). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Ottiene o imposta la trasparenza della firma (valore compreso tra 0,0 (opaco) e 1,0 (chiaro)). Il valore predefinito è 0 (opaco). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Allineamento verticale della firma sulla pagina del documento. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Larghezza della firma sulla pagina del documento in valori di misura (pixel, percentuali o millimetri[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Ottiene o imposta la posizione dell'ordine Z della segnatura del testo. Determina l'ordine di visualizzazione delle segnature sovrapposte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Cancella le risorse interne |

### Osservazioni

**Scopri di più**

* Utilizzo di base della creazione della firma elettronica Timbro da parte di GroupDocs.Signature: [Come firmare un documento con la firma del timbro](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Utilizzo avanzato delle impostazioni della firma elettronica Timbro con GroupDocs.Firma: [Utilizzo avanzato per firmare documenti elettronici con firma Timbro e impostazioni aggiuntive](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Guarda anche

* class [ImageSignOptions](../imagesignoptions)
* spazio dei nomi [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assemblea [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
