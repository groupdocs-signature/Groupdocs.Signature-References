---
title: "ColorResolution"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Ottiene o imposta la risoluzione colore GIF."
type: docs
weight: 30
url: /it/net/groupdocs.signature.options/gifsaveoptions/colorresolution/
---
## GifSaveOptions.ColorResolution property

Ottiene o imposta la risoluzione colore GIF.

```csharp
public byte ColorResolution { get; set; }
```

### Osservazioni

Color Resolution - Numero di bit per colore primario disponibili nell'immagine originale, meno 1. Questo valore rappresenta la dimensione dell'intera palette da cui sono stati selezionati i colori del grafico, non il numero di colori effettivamente usati nel grafico. Per esempio, se il valore in questo campo è 3, allora la palette dell'immagine originale aveva 4 bit per colore primario disponibili per creare l'immagine. Questo valore dovrebbe essere impostato per indicare la ricchezza della palette originale, anche se non tutti i colori dell'intera palette sono disponibili sulla macchina sorgente.

### Vedi anche

* class [GifSaveOptions](../../gifsaveoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
