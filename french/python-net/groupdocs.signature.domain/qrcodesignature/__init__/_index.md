---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise un objet QrCodeSignature avec un identifiant de signature obtenu après un processus de recherche."
type: docs
url: /fr/python-net/groupdocs.signature.domain/qrcodesignature/__init__/
is_root: false
weight: 10
---


## __init__ {#signature_id}

Initialise un objet QrCodeSignature avec un identifiant de signature obtenu après un processus de recherche.

L'identifiant unique est utilisé pour récupérer des propriétés supplémentaires pour cette signature à partir de la couche d'informations de signature du document.

```python
def __init__(self, signature_id):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature_id | `str` | Identifiant unique de la signature obtenu par la méthode sign ou search. |

### Voir aussi
* class [`QrCodeSignature`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/)
