---
title: "color_resolution خاصية"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "دقة ألوان GIF."
type: docs
url: /ar/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

دقة ألوان GIF.

دقة اللون - عدد البتات لكل لون أساسي متاحة في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم اللوحة الكاملة التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل هي 3، فإن لوحة الصورة الأصلية كانت تحتوي على 4 بتات لكل لون أساسي متاحة لإنشاء الصورة. يجب ضبط هذه القيمة للإشارة إلى غنى اللوحة الأصلية، حتى إذا لم يكن كل لون من اللوحة الكاملة متاحًا على الجهاز المصدر.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### انظر أيضًا
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
