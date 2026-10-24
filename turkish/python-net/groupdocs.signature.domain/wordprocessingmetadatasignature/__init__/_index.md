---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belirtilen ad ve boş bir değerle bir WordProcessingMetadataSignature başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Belirtilen ad ve boş bir değerle bir WordProcessingMetadataSignature başlatır.

```python
def __init__(self, name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | WordProcessing Metadata Signature adı. |

### Örnek

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# Ad ve değer ile meta veri imzaları oluşturun
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

Önceden tanımlı değerlerle bir WordProcessing meta veri imzası başlatır.

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

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

### Ayrıca Bakınız
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
