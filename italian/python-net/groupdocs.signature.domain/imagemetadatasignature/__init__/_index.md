---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una firma di metadati immagine con l'identificatore e il valore specificati."
type: docs
url: /it/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Inizializza una firma di metadati immagine con l'identificatore e il valore specificati.

```python
def __init__(self, id, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| id | `System.UInt16` | Identificatore univoco per la firma dei metadati dell'immagine. Vedi le referenze per le specifiche dei tag EXIF per i possibili valori di id. |
| value | `Any` | Il valore dei metadati. |

### Esempio

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

### Vedi anche
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
