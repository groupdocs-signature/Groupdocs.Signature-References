---
title: "propriété do_palette_correction"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le drapeau indiquant si la correction de palette est appliquée."
type: docs
url: /fr/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

Le drapeau indiquant si la correction de palette est appliquée.

La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source seront analysées afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options). Le processus d'analyse prend un certain temps ; cependant, l'image de sortie disposera de la palette de couleurs la mieux adaptée et le résultat sera visuellement meilleur.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### Voir aussi
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
