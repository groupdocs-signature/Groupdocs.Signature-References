---
title: "clone-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Klonen Sie die Signaturinstanz."
type: docs
url: /de/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Klonen Sie die Signaturinstanz.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Beispiel

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Klonen Sie eine Metadaten-Signatur mit einem neuen Wert
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Siehe auch
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
