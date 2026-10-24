---
title: "Classe Event"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta i dettagli standard dell'evento QR-Code."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Rappresenta i dettagli standard dell'evento QR-Code.

Il tipo Event espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Inizializza un'istanza di Event con valori predefiniti. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Confronta questo Event con un altro Event per uguaglianza. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Restituisce il codice hash per l'Event. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | La descrizione dell'evento. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | La data e l'ora di fine dell'evento. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | La posizione dell'evento. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | La data e l'ora di inizio dell'evento. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | Il titolo dell'evento. |

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
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
