---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der MetadataSignOptions‑Klasse mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/metadatasignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der MetadataSignOptions‑Klasse mit Standardwerten.

```python
def __init__(self):
    ...
```

### Beispiel

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

Initialisiert eine neue Instanz von [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) mit Metadaten.

```python
def __init__(self, signatures):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Sammlung von Metadaten‑Signaturen `MetadataSignature`. |

### Beispiel

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

### Siehe auch
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
