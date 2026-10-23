---
title: "فئة Event"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل تفاصيل حدث رمز الاستجابة السريعة القياسي."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

يمثل تفاصيل حدث رمز الاستجابة السريعة القياسي.

يعرض نوع Event الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | يقوم بتهيئة نسخة من Event بالقيم الافتراضية. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | يقارن هذا Event بآخر Event للتحقق من المساواة. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | يعيد رمز التجزئة الخاص بـ Event. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | وصف الحدث. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | تاريخ ووقت انتهاء الحدث. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | موقع الحدث. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | تاريخ ووقت بدء الحدث. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | عنوان الحدث. |

### مثال

```python
from datetime import datetime
from groupdocs.signature.domain.extensions import Event

event_qr = Event()
event_qr.title = "Meeting"
event_qr.description = "Productivity issues"
event_qr.location = "room 408"
event_qr.start_date = datetime(2022, 6, 19, 15, 30, 0)
event_qr.end_date = datetime(2022, 6, 19, 17, 0, 0)
```

### انظر أيضًا
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
