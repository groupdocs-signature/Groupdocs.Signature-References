---
title: "خاصية load_external_resources"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "العلم الذي يحدد ما إذا كان المستند يحمل الموارد الخارجية."
type: docs
url: /ar/python-net/groupdocs.signature.options/loadoptions/load_external_resources/
is_root: false
weight: 2020
---


## load_external_resources property

العلم الذي يحدد ما إذا كان المستند يحمل الموارد الخارجية. هذه الخاصية مهجورة؛ استخدم [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) بدلاً منها، والتي لها معنى عكسي.

LoadExternalResources = True يعادل `SkipExternalResources` = False، وLoadExternalResources = False يعادل `SkipExternalResources` = True. القيمة الافتراضية هي False، مما يعني عدم تحميل الموارد الخارجية إلا إذا تم السماح بذلك صراحةً.

### Definition:
```python
@property
def load_external_resources(self):
    ...
@load_external_resources.setter
def load_external_resources(self, value):
    ...
```

### انظر أيضًا
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
