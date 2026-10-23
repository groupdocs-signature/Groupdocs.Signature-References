---
title: "خاصية reference"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "مرجع دفع الدائن."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/swissqr/reference/
is_root: false
weight: 2070
---


## reference property

مرجع دفع الدائن.

إنه إلزامي لـ IBANs SwissQR (IBANs في النطاق CHxx30000xxxxxx إلى CHxx31999xxxxx). إذا تم تحديده، يجب أن يكون المرجع إما مرجع SwissQR صالح (مطابق لنموذج مرجع ISR) أو مرجع دائن صالح وفقًا لـ ISO 11649 ("RFxxxx"). كلاهما قد يحتوي على مسافات للتنسيق.

### Definition:
```python
@property
def reference(self):
    ...
@reference.setter
def reference(self, value):
    ...
```

### انظر أيضًا
* class [`SwissQR`](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/)
