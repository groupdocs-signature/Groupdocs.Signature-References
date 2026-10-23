---
title: "خاصية return_content_type"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "نوع الملف لمحتوى الصورة المعاد عندما تكون خاصية returncontent مفعلة."
type: docs
url: /ar/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

نوع الملف لمحتوى الصورة المعاد عندما تكون الخاصية `return_content` مفعلة.

إذا لم يتم تعيينه (الافتراضي `None`)، يتم إرجاع محتوى الصورة بالتنسيق الأصلي كما هو معرف في [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). القيم المدعومة هي [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/)، [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/)، و[`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). إذا تم توفير تنسيق غير مدعوم، يتم إرجاع التنسيق الأصلي.

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
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
