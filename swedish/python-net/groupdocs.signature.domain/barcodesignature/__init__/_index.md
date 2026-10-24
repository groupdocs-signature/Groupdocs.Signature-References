---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar ett BarcodeSignature-objekt med en signaturidentifierare som erhållits efter en sökprocess."
type: docs
url: /sv/python-net/groupdocs.signature.domain/barcodesignature/__init__/
is_root: false
weight: 10
---


## __init__ {#signature_id}

Initierar ett BarcodeSignature-objekt med en signaturidentifierare som erhållits efter en sökprocess. Identifieraren används för att hämta ytterligare egenskaper för denna signatur från dokumentets signaturinformationslager.

```python
def __init__(self, signature_id):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signature_id | `str` | Unik signaturidentifierare erhållen av `Sign`- eller `Search`-metoden i `Signature`. |

### Se även
* class [`BarcodeSignature`](/signature/python-net/groupdocs.signature.domain/barcodesignature/)
