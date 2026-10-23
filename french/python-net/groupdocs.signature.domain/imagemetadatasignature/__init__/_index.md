---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une signature de métadonnées d'image avec l'identifiant et la valeur spécifiés."
type: docs
url: /fr/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Initialise une signature de métadonnées d'image avec l'identifiant et la valeur spécifiés.

```python
def __init__(self, id, value):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| id | `System.UInt16` | Identifiant unique pour la signature des métadonnées d'image. Voir les références pour les spécifications des balises EXIF afin d'obtenir les valeurs d'ID possibles. |
| value | `Any` | La valeur des métadonnées. |

### Exemple

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### Voir aussi
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
