---
title: "VerificationResult-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar en instans som behåller resultat från verifieringsprocessen."
type: docs
url: /sv/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Representerar en instans som behåller resultat från verifieringsprocessen.

VerificationResult-typen exponerar följande medlemmar:

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | Destinationsdokumentets storlek. Vid verifiering innehåller denna variabel alltid noll. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | Listan över signaturer som misslyckades med verifieringsprocessen. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | Verifieringsresultatet; True om verifieringsprocessen lyckades, annars False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | Processens verkställningstid i millisekunder. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | Källdokumentets storlek i byte. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | Listan över framgångsrikt verifierade signaturer [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | Det totala antalet bearbetade signaturer. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
