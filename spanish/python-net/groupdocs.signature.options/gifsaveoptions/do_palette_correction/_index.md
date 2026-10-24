---
title: "propiedad do_palette_correction"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La bandera que indica si se aplica la corrección de paleta."
type: docs
url: /es/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

La bandera que indica si se aplica la corrección de paleta.

La corrección de paleta significa que siempre que una imagen se exporta a GIF, los colores de la imagen fuente serán analizados para crear la paleta que mejor coincida (en caso de que la paleta de la imagen no exista o no esté especificada en las opciones). El proceso de análisis lleva algo de tiempo; sin embargo, la imagen de salida tendrá la paleta de colores que mejor coincida y el resultado será visualmente mejor.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### Ver también
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
