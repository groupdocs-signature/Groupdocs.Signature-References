---
title: "Event क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "मानक QR-कोड इवेंट विवरण दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

मानक QR-कोड इवेंट विवरण दर्शाता है।

Event प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | डिफ़ॉल्ट मानों के साथ एक Event इंस्टेंस को प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | इस Event की तुलना किसी अन्य Event से समानता के लिए करता है। |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Event के लिए हैश कोड लौटाता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | इवेंट का विवरण। |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | इवेंट की समाप्ति तिथि और समय। |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | इवेंट का स्थान। |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | इवेंट की प्रारंभ तिथि और समय। |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | इवेंट का शीर्षक। |

### उदाहरण

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

### संबंधित देखें
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
