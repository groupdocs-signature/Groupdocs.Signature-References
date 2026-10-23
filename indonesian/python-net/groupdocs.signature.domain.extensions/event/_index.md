---
title: "Kelas Event"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili detail Acara QR-Code standar."
type: docs
url: /id/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

Mewakili detail Acara QR-Code standar.

Tipe Event menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | Menginisialisasi instance Event dengan nilai default. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | Membandingkan Event ini dengan Event lain untuk kesetaraan. |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Mengembalikan kode hash untuk Event. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | Deskripsi acara. |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | Tanggal dan waktu berakhirnya acara. |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | Lokasi acara. |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | Tanggal dan waktu dimulainya acara. |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | Judul acara. |

### Contoh

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

### Lihat Juga
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
