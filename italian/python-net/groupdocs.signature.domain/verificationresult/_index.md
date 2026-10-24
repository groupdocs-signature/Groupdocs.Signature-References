---
title: "Classe VerificationResult"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Rappresenta un'istanza che conserva i risultati del processo di verifica."
type: docs
url: /it/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Rappresenta un'istanza che conserva i risultati del processo di verifica.

Il tipo VerificationResult espone i seguenti membri:

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | La dimensione del documento di destinazione. Per la verifica questa variabile contiene sempre zero. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | L'elenco delle firme che hanno fallito il processo di verifica. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | Il risultato della verifica; True se il processo di verifica è riuscito, altrimenti False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | Il tempo di esecuzione del processo in millisecondi. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | La dimensione del documento sorgente in byte. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | L'elenco delle firme verificate con successo [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | Il numero totale di firme elaborate. |

### Esempio

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

### Vedi anche
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
