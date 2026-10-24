---
title: "свойство do_palette_correction"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Флаг, указывающий, применяется ли коррекция палитры."
type: docs
url: /ru/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

Флаг, указывающий, применяется ли коррекция палитры.

Коррекция палитры означает, что каждый раз при экспорте изображения в GIF цвета исходного изображения будут анализироваться для построения наиболее подходящей палитры (в случае, если палитра изображения отсутствует или не указана в параметрах). Процесс анализа занимает некоторое время; однако выходное изображение будет иметь наиболее подходящую цветовую палитру, и результат будет визуально лучше.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### См. также
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
