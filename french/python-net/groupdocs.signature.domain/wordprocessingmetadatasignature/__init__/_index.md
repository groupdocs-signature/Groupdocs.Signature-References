---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise un WordProcessingMetadataSignature avec le nom spécifié et une valeur vide."
type: docs
url: /fr/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialise un WordProcessingMetadataSignature avec le nom spécifié et une valeur vide.

```python
def __init__(self, name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Nom de la signature de métadonnées WordProcessing. |

### Exemple

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# Créer des signatures de métadonnées avec un nom et une valeur
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

Initialise une signature de métadonnées de traitement de texte avec des valeurs prédéfinies.

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Voir aussi
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
