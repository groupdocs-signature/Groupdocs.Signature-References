---
title: "خاصية return_content_type"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "نوع الملف لمحتوى الصورة المعاد لتوقيع QR-Code عندما تكون خاصية returncontent مفعلة."
type: docs
url: /ar/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

نوع الملف لمحتوى الصورة المعاد لتوقيع QR-Code عندما تكون خاصية `return_content` مفعلة.

بشكل افتراضي يتم تعيينه إلى `None`، مما يعيد محتوى صورة QR-Code بصيغته الأصلية. يتم تحديد صيغة الصورة في [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). القيم المدعومة هي [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)، [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)، و[`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). إذا تم توفير صيغة غير مدعومة، يتم إرجاع محتوى صورة QR-Code كملف PNG.

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
