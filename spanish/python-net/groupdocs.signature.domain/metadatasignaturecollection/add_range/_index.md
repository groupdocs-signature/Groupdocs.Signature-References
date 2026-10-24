---
title: "método add_range"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Agrega una colección de firmas de metadatos."
type: docs
url: /es/python-net/groupdocs.signature.domain/metadatasignaturecollection/add_range/
is_root: false
weight: 1030
---


## add_range {#signatures}

Agrega una colección de firmas de metadatos.

```python
def add_range(self, signatures):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Colección de firmas para añadir. |

### Ejemplo

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

def sign_docx():
    with Signature("sample.docx") as signature:
        options = MetadataSignOptions()
        signatures = [
            WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
            WordProcessingMetadataSignature("DateCreated", datetime.now()),
            WordProcessingMetadataSignature("DocumentId", 123456),
            WordProcessingMetadataSignature("SignatureId", 123.456),
        ]
        options.signatures.add_range(signatures)
        result = signature.sign("signed.docx", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.name}")
```

### Ver también
* class [`MetadataSignatureCollection`](/signature/python-net/groupdocs.signature.domain/metadatasignaturecollection/)
