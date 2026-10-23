---
title: "propriété pixel_aspect_ratio"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Le rapport d'aspect des pixels du GIF."
type: docs
url: /fr/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

Le rapport d'aspect des pixels du GIF.

Ratio d'aspect du pixel – facteur utilisé pour calculer une approximation du ratio d'aspect du pixel dans l'image originale. Si la valeur du champ n'est pas 0, cette approximation du ratio d'aspect est calculée selon la formule :

Ratio d'aspect = (Pixel Aspect Ratio + 15) / 64

Le Ratio d'aspect du pixel est défini comme le quotient de la largeur du pixel sur sa hauteur. L'intervalle de valeurs dans ce champ permet de spécifier le pixel le plus large à 4 : 1 jusqu'au pixel le plus haut à 1 : 4 par incréments de 1/64.

Valeurs :
- 0 – No aspect ratio information is given.
- 1..255 – Value used in the computation.

### Definition:
```python
@property
def pixel_aspect_ratio(self):
    ...
@pixel_aspect_ratio.setter
def pixel_aspect_ratio(self, value):
    ...
```

### Voir aussi
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
