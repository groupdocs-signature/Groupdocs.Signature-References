---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari kelas MetadataSearchOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas MetadataSearchOptions dengan nilai default.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    print(f"Found {len(result.signatures)} metadata signature(s)")
```

### Lihat Juga
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
