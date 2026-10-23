---
title: "Classe Event"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente les détails d'événement standard du QR‑Code."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Représente les détails d'événement standard du QR‑Code.

Le type Event expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Initialise une instance Event avec les valeurs par défaut. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Compare cet Event avec un autre Event pour vérifier l’égalité. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Renvoie le code de hachage pour l’Event. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | La description de l’événement. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | La date et l’heure de fin de l’événement. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | Le lieu de l’événement. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | La date et l’heure de début de l’événement. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | Le titre de l’événement. |

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
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
