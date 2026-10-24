---
title: "clone metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Klonar en Metadata Signature-instans."
type: docs
url: /sv/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Klonar en Metadata Signature-instans.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Exempel

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Skapa en ny metadata-signatur baserad på den fördefinierade AUTHOR-signaturen
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Klona Metadata Signature-instans med givet värde.

```python
def clone(self, value):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | `Any` | Värde för nytt klonat objekt. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Exempel

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Klona en befintlig metadata‑signatur med ett nytt värde
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Se även
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
