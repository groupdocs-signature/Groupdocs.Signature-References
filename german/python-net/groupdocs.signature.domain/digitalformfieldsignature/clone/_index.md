---
title: "clone-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Klonen einer FormField Signature-Instanz."
type: docs
url: /de/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Klonen einer FormField Signature-Instanz.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### Beispiel

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Klonen Sie eine Metadaten-Signatur mit einem neuen Wert
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Siehe auch
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
