---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "MetadataSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

MetadataSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    print(f"Found {len(result.signatures)} metadata signature(s)")
```

### Ayrıca Bakınız
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
