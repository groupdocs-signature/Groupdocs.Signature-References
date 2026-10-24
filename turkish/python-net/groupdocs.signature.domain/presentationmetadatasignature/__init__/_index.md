---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belirtilen ad ve boş bir değerle bir PresentationMetadataSignature başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Belirtilen ad ve boş bir değerle bir PresentationMetadataSignature başlatır.

```python
def __init__(self, name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | Presentation Metadata Signature adı. |

## __init__ {#name-value}

Önceden tanımlı değerlerle bir PresentationMetadataSignature başlatır.

```python
def __init__(self, name, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | Meta veri imza nesnesinin adı. |
| value | `Any` | Meta veri imzasının değeri. |

### Örnek

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PresentationMetadataSignature

with Signature("sample.ppsx") as signature:
    options = MetadataSignOptions()
    signatures = [
        PresentationMetadataSignature("Author", "Mr. Sherlock Holmes"),
        PresentationMetadataSignature("DateCreated", datetime.now()),
        PresentationMetadataSignature("DocumentId", 123456),
        PresentationMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.ppsx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Ayrıca Bakınız
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
