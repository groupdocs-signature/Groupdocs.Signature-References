---
title: "méthode error"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Écrit un message d'erreur dans la console."
type: docs
url: /fr/python-net/groupdocs.signature.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-ex}

Écrit un message d'erreur dans la console.

Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.

```python
def error(self, message, ex):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| message | `str` | Le message d'erreur. |
| ex | `Exception` | L'exception. |

| Lève | Description |
| :- | :- |
| `ValueError` | Si `ex` est None. |

### Voir aussi
* class [`FileLogger`](/signature/python-net/groupdocs.signature.logging/filelogger/)
