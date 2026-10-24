---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza un WordProcessingMetadataSignature con il nome specificato e un valore vuoto."
type: docs
url: /it/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inizializza un WordProcessingMetadataSignature con il nome specificato e un valore vuoto.

```python
def __init__(self, name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | WordProcessing Metadata Signature nome. |

### Esempio

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# Crea firme di metadati con nome e valore
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

Inizializza una firma di metadati WordProcessing con valori predefiniti.

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

### Vedi anche
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
