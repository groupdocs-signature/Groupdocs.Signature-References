---
title: "pixel_aspect_ratio özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "GIF piksel en-boy oranı."
type: docs
url: /tr/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

GIF piksel en-boy oranı.

Pixel Aspect Ratio – Orijinal görüntüdeki pikselin en‑boy oranının bir yaklaşık değerini hesaplamak için kullanılan faktör. Alanın değeri 0 değilse, bu en‑boy oranı yaklaşık değeri aşağıdaki formüle göre hesaplanır:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

Pixel Aspect Ratio, pikselin genişliğinin yüksekliğine bölümü olarak tanımlanır. Bu alandaki değer aralığı, 4:1 en geniş pikselden 1:4 en yüksek piksele kadar 1/64 artışlarla belirtilmesine olanak tanır.

Değerler:
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

### Ayrıca Bakınız
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
