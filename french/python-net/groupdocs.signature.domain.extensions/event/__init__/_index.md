---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une instance Event avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une instance Event avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

### Exemple

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

### Voir aussi
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
