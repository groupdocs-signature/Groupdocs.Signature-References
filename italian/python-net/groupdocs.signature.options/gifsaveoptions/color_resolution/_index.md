---
title: "proprietà color_resolution"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "La risoluzione colore GIF."
type: docs
url: /it/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

La risoluzione colore GIF.

Color Resolution - Numero di bit per colore primario disponibili nell'immagine originale, meno 1. Questo valore rappresenta la dimensione dell'intera tavolozza da cui sono stati selezionati i colori della grafica, non il numero di colori effettivamente usati nella grafica. Per esempio, se il valore in questo campo è 3, allora la tavolozza dell'immagine originale aveva 4 bit per colore primario disponibili per creare l'immagine. Questo valore dovrebbe essere impostato per indicare la ricchezza della tavolozza originale, anche se non tutti i colori dell'intera tavolozza sono disponibili sulla macchina di origine.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### Vedi anche
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
