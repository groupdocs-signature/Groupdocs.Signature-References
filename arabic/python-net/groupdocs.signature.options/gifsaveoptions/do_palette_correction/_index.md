---
title: "do_palette_correction خاصية"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "العلم الذي يشير إلى ما إذا تم تطبيق تصحيح اللوحة."
type: docs
url: /ar/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

العلم الذي يشير إلى ما إذا تم تطبيق تصحيح اللوحة.

تصحيح اللوحة يعني أنه كلما تم تصدير صورة إلى GIF، سيتم تحليل ألوان الصورة المصدر لبناء أفضل لوحة ألوان مطابقة (في حال عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت؛ ومع ذلك، ستحصل الصورة الناتجة على أفضل لوحة ألوان مطابقة وستكون النتيجة بصريًا أفضل.

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### انظر أيضًا
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
