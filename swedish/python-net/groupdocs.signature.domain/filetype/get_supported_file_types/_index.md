---
title: "get_supported_file_types‑metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Hämtar stödjade filtyper."
type: docs
url: /sv/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Hämtar stödjade filtyper.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Exempel

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### Se även
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
