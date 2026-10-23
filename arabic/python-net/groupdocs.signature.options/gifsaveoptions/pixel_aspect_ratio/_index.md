---
title: "pixel_aspect_ratio خاصية"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "نسبة أبعاد بكسل GIF."
type: docs
url: /ar/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

نسبة أبعاد بكسل GIF.

نسبة أبعاد البكسل – عامل يُستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب لنسبة الأبعاد بناءً على الصيغة:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

يتم تعريف نسبة أبعاد البكسل على أنها ناتج قسمة عرض البكسل على ارتفاعه. يسمح نطاق القيم في هذا الحقل بتحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64.

القيم:
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

### انظر أيضًا
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
