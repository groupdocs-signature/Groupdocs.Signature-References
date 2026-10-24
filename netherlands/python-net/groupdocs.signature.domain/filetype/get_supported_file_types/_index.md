---
title: "get_supported_file_types-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Haalt ondersteunde bestandstypen op."
type: docs
url: /nl/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Haalt ondersteunde bestandstypen op.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Voorbeeld

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### Zie ook
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
