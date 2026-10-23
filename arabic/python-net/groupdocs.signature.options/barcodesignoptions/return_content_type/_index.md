---
title: "خاصية return_content_type"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "نوع الملف لمحتوى الصورة المرجعة لتوقيع الباركود عندما تكون خاصية returncontent مفعلة."
type: docs
url: /ar/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

نوع الملف لمحتوى الصورة المعاد لتوقيع الباركود عندما تكون الخاصية `return_content` مفعلة.

بشكل افتراضي يتم تعيينه إلى `None`، مما يعني أن محتوى صورة الباركود يُرجع بتنسيقه الأصلي. يتم تحديد تنسيق الصورة بواسطة [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). القيم المدعومة هي [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)، [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)، و[`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). إذا تم توفير تنسيق غير مدعوم، سيتم إرجاع محتوى صورة الباركود بتنسيق PNG.

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
