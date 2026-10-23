---
title: "طريقة get_document_info"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحصل على معلومات حول صفحات المستند: أحجامها، أقصى ارتفاع للصفحة، عرض الصفحة ذات أقصى ارتفاع."
type: docs
url: /ar/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

يحصل على معلومات حول صفحات المستند: أحجامها، أقصى ارتفاع للصفحة، عرض الصفحة ذات أقصى ارتفاع.

تعرف على المزيد حول المستند الموقع - نوع الملف، عدد الصفحات والعديد من الخصائص الخاصة بالتنسيق:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### مثال

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number يبدأ من الصفر: 0 هو الصفحة الأولى
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### انظر أيضًا
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
