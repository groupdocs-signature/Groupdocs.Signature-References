---
title: "metodo error"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Scrive un messaggio di errore sulla console."
type: docs
url: /it/python-net/groupdocs.signature.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Scrive un messaggio di errore sulla console.

I messaggi di log error forniscono informazioni su eventi irrecuperabili nel flusso dell'applicazione.

```python
def error(self, message, ex):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| message | `str` | Il messaggio di errore. |
| ex | `Exception` | L'eccezione. |

| Genera | Descrizione |
| :- | :- |
| `ValueError` | Quando `ex` è None. |

### Vedi anche
* class [`ConsoleLogger`](/signature/python-net/groupdocs.signature.logging/consolelogger/)
