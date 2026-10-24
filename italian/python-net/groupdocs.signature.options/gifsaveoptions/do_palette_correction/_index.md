---
title: "proprietà do_palette_correction"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Il flag che indica se viene applicata la correzione della palette."
type: docs
url: /it/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

Il flag che indica se viene applicata la correzione della palette.

La correzione della tavolozza significa che ogni volta che un'immagine viene esportata in GIF i colori dell'immagine sorgente saranno analizzati per costruire la tavolozza più adatta (nel caso in cui la tavolozza dell'immagine non esista o non sia specificata nelle opzioni). Il processo di analisi richiede del tempo; tuttavia, l'immagine di output avrà la tavolozza di colori più corrispondente e il risultato sarà visivamente migliore.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### Vedi anche
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
