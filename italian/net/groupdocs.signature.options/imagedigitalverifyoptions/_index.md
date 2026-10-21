---
title: "ImageDigitalVerifyOptions"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Conserva le opzioni per verificare le firme digitali nelle immagini raster."
type: docs
weight: 1640
url: /it/net/groupdocs.signature.options/imagedigitalverifyoptions/
---
## ImageDigitalVerifyOptions class

Conserva le opzioni per verificare le firme digitali nelle immagini raster.

```csharp
public class ImageDigitalVerifyOptions : VerifyOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageDigitalVerifyOptions](imagedigitalverifyoptions)() | Inizializza una nuova istanza della classe ImageDigitalVerifyOptions per verificare firme digitali (steganografia) in immagini raster. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | Flag per verificare ogni pagina del documento. Il valore predefinito è true. |
| [DetectedProbability](../../groupdocs.signature.options/imagedigitalverifyoptions/detectedprobability) { get; } | Memorizza la probabilità restituita da AnalyzePercentageDigitalSignature (0-100). |
| [DetectionThresholdPercent](../../groupdocs.signature.options/imagedigitalverifyoptions/detectionthresholdpercent) { get; set; } | Percentuale di soglia di rilevamento per l'estrazione parziale (0-100). Il valore predefinito è 75. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | Estensioni aggiuntive per la verifica di opzioni di firma alternative. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | Flag di proprietà valido. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | Numero di pagina del documento da verificare. Se la proprietà non è impostata, tutte le pagine del documento saranno verificate per la prima occorrenza. Il valore minimo è 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | Opzioni di pagina per specificare le pagine da verificare. |
| [Password](../../groupdocs.signature.options/imagedigitalverifyoptions/password) { get; set; } | Password utilizzata per incorporare la firma. |
| [ShapePosition](../../groupdocs.signature.options/verifyoptions/shapeposition) { get; set; } | Specifica la posizione della forma nel layout del documento. Per verificare le firme in intestazioni/piè di pagina. |
| [UseFullDataExtraction](../../groupdocs.signature.options/imagedigitalverifyoptions/usefulldataextraction) { get; set; } | Quando vero, esegue l'estrazione completa dei dati (AnalyzePercentageDigitalSignature) per la massima precisione. |

### Vedi anche

* class [VerifyOptions](../verifyoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
