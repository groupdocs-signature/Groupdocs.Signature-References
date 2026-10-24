---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de MetadataSignOptions‑klasse met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/metadatasignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de MetadataSignOptions‑klasse met standaardwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

Initialiseert een nieuw exemplaar van [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) met metadata.

```python
def __init__(self, signatures):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Collectie van metadata‑handtekeningen `MetadataSignature`. |

### Voorbeeld

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

### Zie ook
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
