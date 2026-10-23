---
title: "get_supported_file_types-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Ruft unterstützte Dateitypen ab."
type: docs
url: /de/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Ruft unterstützte Dateitypen ab.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Beispiel

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### Siehe auch
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
