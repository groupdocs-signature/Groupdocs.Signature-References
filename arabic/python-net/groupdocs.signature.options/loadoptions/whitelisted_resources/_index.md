---
title: "خاصية whitelisted_resources"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "قائمة أجزاء العناوين للموارد الخارجية التي يتم تحميلها حتى عندما تكون LoadOptions.SkipExternalResources صحيحة."
type: docs
url: /ar/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/
is_root: false
weight: 2060
---


## whitelisted_resources property

قائمة أجزاء العناوين للموارد الخارجية التي يتم تحميلها حتى عندما يكون [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) صحيحًا. القيمة الافتراضية هي قائمة فارغة.

يتم تحميل المورد عندما يحتوي عنوانه الكامل على أحد الأجزاء. المقارنة تتجاهل حالة الأحرف، وتُهمل الأجزاء الفارغة. يفضَّل استخدام أجزاء طويلة مثل `"https://cdn.example.com/images/"`: الجزء القصير يطابق أيضًا عناوين أخرى قد تحتوي عليه.

ضبط هذه الخاصية على `None` يمسح القائمة. لا يكون للقائمة أي تأثير عندما تكون [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) خاطئة، لأنه في هذه الحالة يتم تحميل كل مورد خارجي.

### Definition:
```python
@property
def whitelisted_resources(self):
    ...
@whitelisted_resources.setter
def whitelisted_resources(self, value):
    ...
```

### انظر أيضًا
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
