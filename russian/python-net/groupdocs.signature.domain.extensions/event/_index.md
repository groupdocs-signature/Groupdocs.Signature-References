---
title: "Класс Event"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет стандартные детали события QR-Code."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Представляет стандартные детали события QR-Code.

Тип Event раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Инициализирует экземпляр Event со значениями по умолчанию. |

### Методы
| Метод | Описание |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Сравнивает этот Event с другим Event на равенство. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Возвращает хеш‑код для Event. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | Описание события. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | Дата и время окончания события. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | Местоположение события. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | Дата и время начала события. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | Заголовок события. |

### Пример

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

### См. также
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
