---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يقوم بتهيئة نسخة من Event بالقيم الافتراضية."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

يقوم بتهيئة نسخة من Event بالقيم الافتراضية.

```python
def __init__(self):
    ...
```

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
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
