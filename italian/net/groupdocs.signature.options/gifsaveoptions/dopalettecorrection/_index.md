---
title: "DoPaletteCorrection"
second_title: "GroupDocs.Signature per .NET Riferimento API"
description: "Ottiene o imposta un valore che indica se viene applicata la correzione della palette."
type: docs
weight: 40
url: /it/net/groupdocs.signature.options/gifsaveoptions/dopalettecorrection/
---
## GifSaveOptions.DoPaletteCorrection property

Ottiene o imposta un valore che indica se viene applicata la correzione della palette.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Osservazioni

La correzione della palette significa che ogni volta che l'immagine viene esportata in GIF i colori dell'immagine sorgente saranno analizzati per creare la palette più adatta (nel caso in cui la Palette dell'immagine non esista o non sia specificata nelle opzioni). Il processo di analisi richiede del tempo, tuttavia l'immagine di output avrà la palette di colori più adatta e il risultato sarà visivamente migliore.

### Vedi anche

* class [GifSaveOptions](../../gifsaveoptions)
* namespace [GroupDocs.Signature.Options](../../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.signature.dll -->
