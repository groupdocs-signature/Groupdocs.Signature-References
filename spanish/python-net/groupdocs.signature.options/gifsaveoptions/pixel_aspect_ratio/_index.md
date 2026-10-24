---
title: "propiedad pixel_aspect_ratio"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La relación de aspecto de píxel del GIF."
type: docs
url: /es/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

La relación de aspecto de píxel del GIF.

Relación de aspecto del píxel – factor utilizado para calcular una aproximación de la relación de aspecto del píxel en la imagen original. Si el valor del campo no es 0, esta aproximación de la relación de aspecto se calcula basándose en la fórmula:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

El Pixel Aspect Ratio se define como el cociente del ancho del píxel sobre su altura. El rango de valores en este campo permite especificar el píxel más ancho de 4:1 hasta el píxel más alto de 1:4 en incrementos de 1/64.

Valores:
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

### Ver también
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
