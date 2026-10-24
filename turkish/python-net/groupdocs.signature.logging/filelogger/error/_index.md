---
title: "error yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Hata mesajını konsola yazar."
type: docs
url: /tr/python-net/groupdocs.signature.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Hata mesajını konsola yazar.

Error günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.

```python
def error(self, message, ex):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| message | `str` | Error mesajı. |
| ex | `Exception` | İstisna. |

| Kaldırır | Açıklama |
| :- | :- |
| `ValueError` | Eğer `ex` None ise. |

### Ayrıca Bakınız
* class [`FileLogger`](/signature/python-net/groupdocs.signature.logging/filelogger/)
