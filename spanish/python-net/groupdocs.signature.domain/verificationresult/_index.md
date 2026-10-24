---
title: "Clase VerificationResult"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa una instancia que conserva los resultados del proceso de verificación."
type: docs
url: /es/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Representa una instancia que conserva los resultados del proceso de verificación.

El tipo VerificationResult expone los siguientes miembros:

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | El tamaño del documento de destino. Para la verificación, esta variable siempre contiene cero. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | La lista de firmas que fallaron en el proceso de verificación. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | El resultado de la verificación; True si el proceso de verificación fue exitoso, de lo contrario False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | El tiempo de ejecución del proceso en milisegundos. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | El tamaño del documento fuente en bytes. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | La lista de firmas verificadas con éxito [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | El número total de firmas procesadas. |

### Ejemplo

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

### Ver también
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
