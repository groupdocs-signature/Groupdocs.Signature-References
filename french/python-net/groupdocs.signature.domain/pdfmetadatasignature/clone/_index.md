---
title: "méthode clone"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Cloner l'instance de signature de métadonnées."
type: docs
url: /fr/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Cloner l'instance de signature de métadonnées.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Exemple

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Cloner une signature de métadonnées standard avec une nouvelle valeur
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Clone une instance de signature de métadonnées PDF avec la valeur donnée.

```python
def clone(self, value):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| value | `Any` | Valeur pour le nouvel objet cloné. |

**Returns:** A cloned metadata signature instance.

### Exemple

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Cloner une signature de métadonnées existante avec une nouvelle valeur
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Voir aussi
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
