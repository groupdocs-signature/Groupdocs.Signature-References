---
title: "metodo get_supported_file_types"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Recupera i tipi di file supportati."
type: docs
url: /it/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Recupera i tipi di file supportati.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Esempio

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### Vedi anche
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
