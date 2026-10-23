---
title: "Κλάση Event"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις τυπικές λεπτομέρειες γεγονότος QR‑Code."
type: docs
url: /el/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Αντιπροσωπεύει τις τυπικές λεπτομέρειες γεγονότος QR‑Code.

Ο τύπος Event εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Αρχικοποιεί ένα αντικείμενο Event με προεπιλεγμένες τιμές. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Συγκρίνει αυτό το Event με ένα άλλο Event για ισότητα. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Επιστρέφει τον κωδικό κατακερματισμού για το Event. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | Η περιγραφή του γεγονότος. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | Η ημερομηνία και ώρα λήξης του γεγονότος. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | Η τοποθεσία του γεγονότος. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | Η ημερομηνία και ώρα έναρξης του γεγονότος. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | Ο τίτλος του γεγονότος. |

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
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
