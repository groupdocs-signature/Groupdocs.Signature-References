---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belirtilen tanımlayıcı ve değerle bir Image Metadata Signature başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Belirtilen tanımlayıcı ve değerle bir Image Metadata Signature başlatır.

```python
def __init__(self, id, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| id | `System.UInt16` | Görüntü Meta Verisi İmzası için benzersiz tanımlayıcı. Olası kimlik değerleri için EXIF etiket spesifikasyonlarına ilişkin referanslara bakın. |
| value | `Any` | Meta veri değeri. |

### Örnek

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### Ayrıca Bakınız
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
