---
title: "Händelseklass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar standard‑QR‑Kod‑evenemangsdetaljer."
type: docs
url: /sv/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Representerar standard‑QR‑Kod‑evenemangsdetaljer.

Händelsetypen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Initierar en Event-instans med standardvärden. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Jämför detta Event med ett annat Event för likhet. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Returnerar hashkoden för Event. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | Beskrivningen av eventet. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | Evenemangets slutdatum och tid. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | Platsen för evenemanget. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | Evenemangets startdatum och tid. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | Evenemangets titel. |

### Exempel

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

### Se även
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
