---
title: "get_supported_file_types yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Desteklenen dosya türlerini alır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Desteklenen dosya türlerini alır.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Örnek

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### Ayrıca Bakınız
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
