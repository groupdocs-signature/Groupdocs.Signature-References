---
title: "metode error"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menulis pesan error ke konsol."
type: docs
url: /id/python-net/groupdocs.signature.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Menulis pesan error ke konsol.

Pesan log Error menyediakan informasi tentang kejadian yang tidak dapat dipulihkan dalam alur aplikasi.

```python
def error(self, message, ex):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| message | `str` | Pesan error. |
| ex | `Exception` | Pengecualian. |

| Melepaskan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `ex` bernilai None. |

### Lihat Juga
* class [`ConsoleLogger`](/signature/python-net/groupdocs.signature.logging/consolelogger/)
