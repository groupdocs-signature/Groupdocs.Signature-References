---
title: "μέθοδος error"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Γράφει ένα μήνυμα σφάλματος στην κονσόλα."
type: docs
url: /el/python-net/groupdocs.signature.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Γράφει ένα μήνυμα σφάλματος στην κονσόλα.

Τα μηνύματα καταγραφής Error παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

```python
def error(self, message, ex):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| message | `str` | Το μήνυμα error. |
| ex | `Exception` | Η εξαίρεση. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `ex` είναι None. |

### Δείτε επίσης
* class [`ConsoleLogger`](/signature/python-net/groupdocs.signature.logging/consolelogger/)
