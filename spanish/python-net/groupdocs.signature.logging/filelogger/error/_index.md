---
title: "método error"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Escribe un mensaje de error en la consola."
type: docs
url: /es/python-net/groupdocs.signature.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Escribe un mensaje de error en la consola.

Los mensajes de registro Error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.

```python
def error(self, message, ex):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| message | `str` | El mensaje de error. |
| ex | `Exception` | La excepción. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `ex` es None. |

### Ver también
* class [`FileLogger`](/signature/python-net/groupdocs.signature.logging/filelogger/)
