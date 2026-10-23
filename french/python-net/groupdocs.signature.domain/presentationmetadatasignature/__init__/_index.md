---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise un PresentationMetadataSignature avec le nom spécifié et une valeur vide."
type: docs
url: /fr/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialise un PresentationMetadataSignature avec le nom spécifié et une valeur vide.

```python
def __init__(self, name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Nom de la signature de métadonnées de présentation. |

## __init__ {#name-value}

Initialise un PresentationMetadataSignature avec des valeurs prédéfinies.

```python
def __init__(self, name, value):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Nom de l'objet de signature de métadonnées. |
| value | `Any` | Valeur de la signature de métadonnées. |

### Exemple

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PresentationMetadataSignature

with Signature("sample.ppsx") as signature:
    options = MetadataSignOptions()
    signatures = [
        PresentationMetadataSignature("Author", "Mr. Sherlock Holmes"),
        PresentationMetadataSignature("DateCreated", datetime.now()),
        PresentationMetadataSignature("DocumentId", 123456),
        PresentationMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.ppsx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Voir aussi
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
