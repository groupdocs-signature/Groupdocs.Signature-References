---
title: "خاصية return_content_type"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "The file type لمحتوى الصورة المعادة لتوقيع الباركود عندما تكون خاصية returncontent مفعلة."
type: docs
url: /ar/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

نوع الملف لمحتوى الصورة المُعاد لتوقيع الباركود عندما تكون خاصية `return_content` مفعلة.

بشكل افتراضي تكون القيمة None، مما يعيد صورة الباركود بصيغتها الأصلية كما هو محدد في [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/).

القيم المدعومة هي [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)، [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)، و[`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). إذا تم توفير قيمة غير هذه، سيتم إرجاع الصورة بصيغة PNG.

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### انظر أيضًا
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
