---
title: "clone-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Klone Metadaten-Signatur-Instanz."
type: docs
url: /de/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Klone Metadaten-Signatur-Instanz.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Beispiel

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Klonen Sie eine Standard-Metadaten-Signatur mit einem neuen Wert
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Klont eine PDF-Metadaten-Signatur-Instanz mit dem angegebenen Wert.

```python
def clone(self, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | `Any` | Wert für das neu geklonte Objekt. |

**Returns:** A cloned metadata signature instance.

### Beispiel

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Klonen Sie eine vorhandene Metadaten-Signatur mit einem neuen Wert
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Siehe auch
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
