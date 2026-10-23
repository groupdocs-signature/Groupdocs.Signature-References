---
title: "méthode get_supported_file_types"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Récupère les types de fichiers pris en charge."
type: docs
url: /fr/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Récupère les types de fichiers pris en charge.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Exemple

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### Voir aussi
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
