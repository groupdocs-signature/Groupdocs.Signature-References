---
title: "método get_supported_file_types"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Recupera los tipos de archivo compatibles."
type: docs
url: /es/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Recupera los tipos de archivo compatibles.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Ejemplo

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### Ver también
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
