---
title: "Event-Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt die Standard‑QR‑Code‑Ereignisdaten dar."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Stellt die Standard‑QR‑Code‑Ereignisdaten dar.

Der Event-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Initialisiert eine Event-Instanz mit Standardwerten. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Vergleicht dieses Event mit einem anderen Event auf Gleichheit. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Gibt den Hashcode für das Event zurück. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | Die Beschreibung des Events. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | Das Enddatum und die Uhrzeit des Events. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | Der Ort des Events. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | Das Startdatum und die Uhrzeit des Events. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | Der Titel des Events. |

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
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
