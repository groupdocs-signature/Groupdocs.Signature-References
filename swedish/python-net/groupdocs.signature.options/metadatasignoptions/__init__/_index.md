---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av MetadataSignOptions‑klassen med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/metadatasignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av MetadataSignOptions‑klassen med standardvärden.

```python
def __init__(self):
    ...
```

### Exempel

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

Initierar en ny instans av [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/) med metadata.

```python
def __init__(self, signatures):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Samling av metadata‑signaturer `MetadataSignature`. |

### Exempel

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

### Se även
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
