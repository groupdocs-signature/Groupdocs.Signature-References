---
title: "Event sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Standart QR-Kod Etkinlik ayrıntılarını temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Standart QR-Kod Etkinlik ayrıntılarını temsil eder.

Event türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Event örneğini varsayılan değerlerle başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Bu Event'i başka bir Event ile eşitlik açısından karşılaştırır. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Event için hash kodunu döndürür. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | Etkinliğin açıklaması. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | Etkinliğin bitiş tarihi ve saati. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | Etkinliğin konumu. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | Etkinliğin başlangıç tarihi ve saati. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | Etkinlik başlığı. |

### Örnek

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

### Ayrıca Bakınız
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
