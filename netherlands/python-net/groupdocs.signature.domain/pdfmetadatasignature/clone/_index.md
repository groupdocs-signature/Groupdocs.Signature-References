---
title: "clone methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Kloon Metadata Signature‑instantie."
type: docs
url: /nl/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Kloon Metadata Signature‑instantie.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Voorbeeld

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Kloon een standaard metadatahandtekening met een nieuwe waarde
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Kloont een PDF-metadatahandtekening‑instantie met de opgegeven waarde.

```python
def clone(self, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | `Any` | Waarde voor het nieuw gekloonde object. |

**Returns:** A cloned metadata signature instance.

### Voorbeeld

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Kloon een bestaande metadata‑handtekening met een nieuwe waarde
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Zie ook
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
