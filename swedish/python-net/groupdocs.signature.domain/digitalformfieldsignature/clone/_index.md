---
title: "clone metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Klonar FormField Signature-instans."
type: docs
url: /sv/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Klonar FormField Signature-instans.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### Exempel

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Klona en metadata‑signatur med ett nytt värde
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Se även
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
