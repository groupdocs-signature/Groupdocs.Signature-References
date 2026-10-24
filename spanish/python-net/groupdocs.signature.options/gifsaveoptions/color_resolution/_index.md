---
title: "propiedad color_resolution"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La resolución de color del GIF."
type: docs
url: /es/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

La resolución de color del GIF.

Resolución de color - Número de bits por color primario disponible en la imagen original, menos 1. Este valor representa el tamaño de toda la paleta de la que se seleccionaron los colores del gráfico, no el número de colores realmente usados en el gráfico. Por ejemplo, si el valor en este campo es 3, entonces la paleta de la imagen original tenía 4 bits por color primario disponibles para crear la imagen. Este valor debe establecerse para indicar la riqueza de la paleta original, incluso si no todos los colores de la paleta completa están disponibles en la máquina fuente.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### Ver también
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
