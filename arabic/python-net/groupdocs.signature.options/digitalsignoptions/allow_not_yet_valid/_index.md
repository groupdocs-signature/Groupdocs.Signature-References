---
title: "خاصية allow_not_yet_valid"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "العلم الذي يسمح بالتوقيع بشهادة لم يبدأ بعد فترة صلاحيتها."
type: docs
url: /ar/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/
is_root: false
weight: 2020
---


## allow_not_yet_valid property

العلم الذي يسمح بالتوقيع باستخدام شهادة لم يبدأ بعد فترة صلاحيتها. القيمة الافتراضية هي False؛ التوقيع بهذه الشهادة يثير `GroupDocsSignatureException` ولا يتم توقيع المستند.

المصادقون يبلغون عن توقيع تم إنشاؤه قبل أن تصبح الشهادة صالحة على أنه غير صالح. عادةً ما تُصدر مثل هذه الشهادة لتاريخ لاحق، أو قد تكون ساعة الحاسوب غير صحيحة. عندما يكون هذا العلم True، يتم توقيع المستند، ويُكتب تحذير إلى السجل المحدد في [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

يتم مقارنة الشهادة بالوقت الحالي بتوقيت UTC. ينطبق هذا العلم على نفس الشهادات كما في [`DigitalSignOptions.AllowExpired`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/)، الذي يتحكم في الشهادات التي انتهت فترة صلاحيتها.

### Definition:
```python
@property
def allow_not_yet_valid(self):
    ...
@allow_not_yet_valid.setter
def allow_not_yet_valid(self, value):
    ...
```

### انظر أيضًا
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
