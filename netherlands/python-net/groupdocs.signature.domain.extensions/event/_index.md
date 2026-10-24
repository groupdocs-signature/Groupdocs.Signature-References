---
title: "Event-klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Geeft de standaard QR-code-evenementdetails weer."
type: docs
url: /nl/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Geeft de standaard QR-code-evenementdetails weer.

Het type Event bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Initialiseert een Event‑instantie met standaardwaarden. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Vergelijkt dit Event met een ander Event op gelijkheid. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Retourneert de hashcode voor het Event. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | De beschrijving van het evenement. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | De einddatum en -tijd van het evenement. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | De locatie van het evenement. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | De startdatum en -tijd van het evenement. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | De titel van het evenement. |

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
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
