---
title: "свойство color_resolution"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Разрешение цвета GIF."
type: docs
url: /ru/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

Разрешение цвета GIF.

Разрешение цвета — количество битов на основной цвет, доступных оригинальному изображению, минус 1. Это значение представляет размер всей палитры, из которой были выбраны цвета графики, а не количество фактически использованных в графике цветов. Например, если значение в этом поле равно 3, то палитра оригинального изображения имела 4 бита на основной цвет, доступных для создания изображения. Это значение следует установить, чтобы указать насыщенность оригинальной палитры, даже если не каждый цвет из полной палитры доступен на исходном устройстве.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### См. также
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
