---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una PresentationMetadataSignature con il nome specificato e un valore vuoto."
type: docs
url: /it/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inizializza una PresentationMetadataSignature con il nome specificato e un valore vuoto.

```python
def __init__(self, name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Nome della firma di metadati di presentazione. |

## __init__ {#name-value}

Inizializza una PresentationMetadataSignature con valori predefiniti.

```python
def __init__(self, name, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Nome dell'oggetto firma di metadati. |
| value | `Any` | Valore della firma di metadati. |

### Esempio

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

### Vedi anche
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
