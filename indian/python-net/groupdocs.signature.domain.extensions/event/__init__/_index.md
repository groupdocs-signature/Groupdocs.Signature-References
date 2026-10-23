---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ एक Event इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ एक Event इंस्टेंस को प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

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

### संबंधित देखें
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
