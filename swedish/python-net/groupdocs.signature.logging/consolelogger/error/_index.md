---
title: "error metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Skriver ett felmeddelande till konsolen."
type: docs
url: /sv/python-net/groupdocs.signature.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Skriver ett felmeddelande till konsolen.

Fel-loggmeddelanden ger information om oåterställbara händelser i applikationsflödet.

```python
def error(self, message, ex):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| message | `str` | Felmeddelandet. |
| ex | `Exception` | Undantaget. |

| Utlöser | Beskrivning |
| :- | :- |
| `ValueError` | När `ex` är None. |

### Se även
* class [`ConsoleLogger`](/signature/python-net/groupdocs.signature.logging/consolelogger/)
