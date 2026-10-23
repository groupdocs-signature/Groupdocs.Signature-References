---
title: "طريقة error"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يكتب رسالة خطأ إلى وحدة التحكم."
type: docs
url: /ar/python-net/groupdocs.signature.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

يكتب رسالة خطأ إلى وحدة التحكم.

توفر رسائل سجل Error معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.

```python
def error(self, message, ex):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| message | `str` | رسالة الخطأ. |
| ex | `Exception` | الاستثناء. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `ex` هو None. |

### انظر أيضًا
* class [`FileLogger`](/signature/python-net/groupdocs.signature.logging/filelogger/)
