---
title: "méthode clone"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Clone une instance de Metadata Signature."
type: docs
url: /fr/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Clone une instance de Metadata Signature.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Exemple

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Créez une nouvelle signature metadata basée sur la signature AUTHOR prédéfinie
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Clone une instance de Metadata Signature avec la valeur donnée.

```python
def clone(self, value):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| value | `Any` | Valeur pour le nouvel objet cloné. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Exemple

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Cloner une signature de métadonnées existante avec une nouvelle valeur
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Voir aussi
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
