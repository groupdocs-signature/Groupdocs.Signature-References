---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una instancia de Event con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una instancia de Event con valores predeterminados.

```python
def __init__(self):
    ...
```

### Ejemplo

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

### Ver también
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
