---
title: "propriété color_resolution"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "La résolution de couleur du GIF."
type: docs
url: /fr/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

La résolution de couleur du GIF.

Résolution des couleurs - Nombre de bits par couleur primaire disponibles dans l'image originale, moins 1. Cette valeur représente la taille de l'ensemble de la palette à partir de laquelle les couleurs du graphique ont été sélectionnées, et non le nombre de couleurs réellement utilisées dans le graphique. Par exemple, si la valeur de ce champ est 3, alors la palette de l'image originale disposait de 4 bits par couleur primaire pour créer l'image. Cette valeur doit être définie pour indiquer la richesse de la palette originale, même si toutes les couleurs de la palette complète ne sont pas disponibles sur la machine source.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### Voir aussi
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
