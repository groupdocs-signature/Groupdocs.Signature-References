---
title: "error-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Schrijft een foutmelding naar de console."
type: docs
url: /nl/python-net/groupdocs.signature.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Schrijft een foutmelding naar de console.

Error-logberichten bieden informatie over onherstelbare gebeurtenissen in de applicatiestroom.

```python
def error(self, message, ex):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| message | `str` | Het foutbericht. |
| ex | `Exception` | De uitzondering. |

| Verhoogt | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `ex` None is. |

### Zie ook
* class [`ConsoleLogger`](/signature/python-net/groupdocs.signature.logging/consolelogger/)
