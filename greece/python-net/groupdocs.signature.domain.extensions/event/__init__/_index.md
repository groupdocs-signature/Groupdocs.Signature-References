---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα αντικείμενο Event με προεπιλεγμένες τιμές."
type: docs
url: /el/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα αντικείμενο Event με προεπιλεγμένες τιμές.

```python
def __init__(self):
    ...
```

### Παράδειγμα

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

### Δείτε επίσης
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
