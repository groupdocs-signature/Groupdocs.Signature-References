---
title: "clone-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Klont eine Instanz von Metadata Signature."
type: docs
url: /de/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Klont eine Instanz von Metadata Signature.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Beispiel

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Erstelle eine neue Metadaten‑Signatur basierend auf der vordefinierten AUTHOR‑Signatur
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Klone eine Metadata Signature-Instanz mit dem angegebenen Wert.

```python
def clone(self, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | `Any` | Wert für neues geklontes Objekt. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Beispiel

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Klonen Sie eine vorhandene Metadaten-Signatur mit einem neuen Wert
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Siehe auch
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
