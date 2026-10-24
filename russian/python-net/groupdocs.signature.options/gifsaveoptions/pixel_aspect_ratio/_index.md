---
title: "свойство pixel_aspect_ratio"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Соотношение сторон пикселя GIF."
type: docs
url: /ru/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

Соотношение сторон пикселя GIF.

Pixel Aspect Ratio – фактор, используемый для вычисления приближённого соотношения сторон пикселя в оригинальном изображении. Если значение поля не равно 0, это приближение соотношения сторон вычисляется по формуле:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

Pixel Aspect Ratio определяется как отношение ширины пикселя к его высоте. Диапазон значений в этом поле позволяет задавать самый широкий пиксель 4:1 до самого высокого пикселя 1:4 с шагом 1/64.

Значения:
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

### См. также
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
