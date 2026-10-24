---
title: "clone metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Klona Metadata Signature-instans."
type: docs
url: /sv/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Klona Metadata Signature-instans.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Exempel

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Klona en standard‑metadata‑signatur med ett nytt värde
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Klonar en PDF-metadata-signaturinstans med det angivna värdet.

```python
def clone(self, value):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | `Any` | Värde för det nya klonade objektet. |

**Returns:** A cloned metadata signature instance.

### Exempel

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Klona en befintlig metadata‑signatur med ett nytt värde
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Se även
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
