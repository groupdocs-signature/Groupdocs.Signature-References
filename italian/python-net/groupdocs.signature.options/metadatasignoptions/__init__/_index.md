---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe MetadataSignOptions con valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/metadatasignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe MetadataSignOptions con valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    options.signatures.add(
        WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
    )
    result = signature.sign("signed.docx", options)
```

## __init__ {#signatures}

Inizializza una nuova istanza di [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) con i metadati.

```python
def __init__(self, signatures):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Raccolta di firme di metadati `MetadataSignature`. |

### Esempio

```python
from datetime import datetime
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

signatures = [
    WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes"),
    WordProcessingMetadataSignature("DateCreated", datetime.now()),
]

options = MetadataSignOptions(signatures=signatures)
```

### Vedi anche
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
