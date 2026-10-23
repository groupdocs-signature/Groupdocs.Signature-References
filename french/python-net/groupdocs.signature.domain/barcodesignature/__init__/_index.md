---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise un objet BarcodeSignature avec un identifiant de signature obtenu après un processus de recherche."
type: docs
url: /fr/python-net/groupdocs.signature.domain/barcodesignature/__init__/
is_root: false
weight: 10
---


## __init__ {#signature_id}

Initialise un objet BarcodeSignature avec un identifiant de signature obtenu après un processus de recherche. L'identifiant est utilisé pour récupérer des propriétés supplémentaires pour cette signature à partir de la couche d'informations de signature du document.

```python
def __init__(self, signature_id):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signature_id | `str` | Identifiant de signature unique obtenu par la méthode `Sign` ou `Search` de `Signature`. |

### Voir aussi
* class [`BarcodeSignature`](/signature/python-net/groupdocs.signature.domain/barcodesignature/)
