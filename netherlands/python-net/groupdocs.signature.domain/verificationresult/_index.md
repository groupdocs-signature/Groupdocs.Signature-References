---
title: "VerificationResult klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt een instantie voor die resultaten van het verificatieproces bijhoudt."
type: docs
url: /nl/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Stelt een instantie voor die resultaten van het verificatieproces bijhoudt.

Het VerificationResult-type geeft de volgende leden weer:

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | De grootte van het bestemmingsdocument. Voor verificatie bevat deze variabele altijd nul. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | De lijst met handtekeningen die de verificatieprocedure hebben gefaald. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | Het verificatieresultaat; True als het verificatieproces succesvol was, anders False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | De uitvoeringstijd van het proces in milliseconden. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | De grootte van het brondocument in bytes. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | De lijst met succesvol geverifieerde handtekeningen [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | Het totale aantal verwerkte handtekeningen. |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
