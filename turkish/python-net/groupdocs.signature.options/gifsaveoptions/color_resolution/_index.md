---
title: "color_resolution özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "GIF renk çözünürlüğü."
type: docs
url: /tr/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

GIF renk çözünürlüğü.

Color Resolution - Orijinal görüntüdeki birincil renk başına mevcut bit sayısı, 1 eksik. Bu değer, grafikte seçilen renklerin alındığı tüm paletin boyutunu temsil eder, grafikte gerçekte kullanılan renk sayısını değil. Örneğin, bu alandaki değer 3 ise, orijinal görüntünün paleti görüntüyü oluşturmak için birincil renk başına 4 bit içeriyordu. Bu değer, tüm paletin her renk kaynağında mevcut olmasa bile orijinal paletin zenginliğini göstermek için ayarlanmalıdır.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### Ayrıca Bakınız
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
