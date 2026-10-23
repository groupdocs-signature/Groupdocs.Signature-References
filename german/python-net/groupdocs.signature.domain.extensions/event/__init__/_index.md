---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine Event-Instanz mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine Event-Instanz mit Standardwerten.

```python
def __init__(self):
    ...
```

### Beispiel

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

### Siehe auch
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
