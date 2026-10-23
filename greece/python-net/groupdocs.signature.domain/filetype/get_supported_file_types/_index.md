---
title: "μέθοδος get_supported_file_types"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Ανακτά τους υποστηριζόμενους τύπους αρχείων."
type: docs
url: /el/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Ανακτά τους υποστηριζόμενους τύπους αρχείων.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Παράδειγμα

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### Δείτε επίσης
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
