---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een Event‑instantie met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een Event‑instantie met standaardwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

### Zie ook
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
