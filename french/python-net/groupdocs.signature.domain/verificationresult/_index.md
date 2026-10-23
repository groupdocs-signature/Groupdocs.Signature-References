---
title: "Classe VerificationResult"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Représente une instance qui conserve les résultats du processus de vérification."
type: docs
url: /fr/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Représente une instance qui conserve les résultats du processus de vérification.

Le type VerificationResult expose les membres suivants :

### Propriétés
| Propriété | Description |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | La taille du document de destination. Pour la vérification, cette variable contient toujours zéro. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | La liste des signatures qui ont échoué au processus de vérification. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | Le résultat de la vérification ; True si le processus de vérification a réussi, sinon False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | Le temps d'exécution du processus en millisecondes. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | La taille du document source en octets. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | La liste des signatures vérifiées avec succès [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | Le nombre total de signatures traitées. |

### Exemple

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

### Voir aussi
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
