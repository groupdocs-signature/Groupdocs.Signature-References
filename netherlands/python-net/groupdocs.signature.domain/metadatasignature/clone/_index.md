---
title: "clone methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Kloont een Metadata Signature instance."
type: docs
url: /nl/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Kloont een Metadata Signature instance.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Voorbeeld

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Maak een nieuwe metadata-handtekening op basis van de vooraf gedefinieerde AUTHOR-handtekening
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Kloon Metadata Signature instance met de opgegeven waarde.

```python
def clone(self, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | `Any` | Waarde voor nieuw gekloond object. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Voorbeeld

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Kloon een bestaande metadata‑handtekening met een nieuwe waarde
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Zie ook
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
