---
title: "Clase Event"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa los detalles estándar del evento QR-Code."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Representa los detalles estándar del evento QR-Code.

El tipo Event expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Inicializa una instancia de Event con valores predeterminados. |

### Métodos
| Método | Descripción |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Compara este Event con otro Event para determinar igualdad. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Devuelve el código hash para el Event. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | La descripción del evento. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | La fecha y hora de finalización del evento. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | La ubicación del evento. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | La fecha y hora de inicio del evento. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | El título del evento. |

### Ejemplo

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

### Ver también
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
