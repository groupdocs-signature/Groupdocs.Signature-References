---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza un'istanza di Event con valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza un'istanza di Event con valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

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

### Vedi anche
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
