---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует экземпляр Event со значениями по умолчанию."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/event/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует экземпляр Event со значениями по умолчанию.

```python
def __init__(self):
    ...
```

### Пример

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

### См. также
* class [`Event`](/signature/python-net/groupdocs.signature.domain.extensions/event/)
