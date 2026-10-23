---
title: "error Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Schreibt eine Fehlermeldung in die Konsole."
type: docs
url: /de/python-net/groupdocs.signature.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Schreibt eine Fehlermeldung in die Konsole.

Error-Protokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

```python
def error(self, message, ex):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| message | `str` | Die Fehlermeldung. |
| ex | `Exception` | Die Ausnahme. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `ex` None ist. |

### Siehe auch
* class [`FileLogger`](/signature/python-net/groupdocs.signature.logging/filelogger/)
