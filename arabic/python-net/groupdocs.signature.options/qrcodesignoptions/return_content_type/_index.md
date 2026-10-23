---
title: "خاصية return_content_type"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "نوع ملف محتوى الصورة المعادة لتوقيع QR‑Code عندما تكون خاصية returncontent مفعلة."
type: docs
url: /ar/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

نوع الملف لمحتوى الصورة المعاد لتوقيع QR‑Code عندما تكون الخاصية `return_content` مفعلة.

بشكل افتراضي تكون `None`، مما يعيد محتوى صورة QR‑Code بصيغتها الأصلية كما هو محدد في [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/).

القيم المدعومة هي [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)، [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)، و[`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). إذا تم توفير تنسيق غير مدعوم، يتم إرجاع المحتوى بصيغة PNG.

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
