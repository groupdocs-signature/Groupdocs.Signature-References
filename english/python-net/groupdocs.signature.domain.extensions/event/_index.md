---
title: Event class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents standard QR-Code Event details."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Represents standard QR-Code Event details.

The Event type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Initializes an Event instance with default values. |

### Methods
| Method | Description |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Compares this Event with another Event for equality. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Returns the hash code for the Event. |

### Properties
| Property | Description |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | The description of the event. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | The event end date and time. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | The location of the event. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | The event start date and time. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | The event title. |

### Example

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

### See Also
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
