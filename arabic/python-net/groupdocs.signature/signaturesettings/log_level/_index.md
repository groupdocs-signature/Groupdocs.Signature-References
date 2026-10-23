---
title: "خاصية log_level"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "علامات مستوى السجل التي تحدد أنواع الرسائل التي يتم تمريرها إلى SignatureSettings.Logger."
type: docs
url: /ar/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

العلم الذي يحدد مستويات السجل والذي يحدد أي أنواع الرسائل يتم تمريرها إلى [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

القيمة هي مجموعة من أعلام `LogLevel` التي يمكن دمجها، على سبيل المثال `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` لا يسجل شيئًا. الافتراضي هو `LogLevel.All`: الأخطاء، التحذيرات والتتبع.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### انظر أيضًا
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
