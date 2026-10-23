---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine Bild‑Metadaten‑Signatur mit dem angegebenen Bezeichner und Wert."
type: docs
url: /de/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Initialisiert eine Bild‑Metadaten‑Signatur mit dem angegebenen Bezeichner und Wert.

```python
def __init__(self, id, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| id | `System.UInt16` | Eindeutiger Bezeichner für die Image Metadata Signature. Siehe Referenzen für EXIF-Tag-Spezifikationen für mögliche ID-Werte. |
| value | `Any` | Der Metadatenwert. |

### Beispiel

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

### Siehe auch
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
