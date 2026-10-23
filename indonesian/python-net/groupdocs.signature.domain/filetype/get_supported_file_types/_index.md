---
title: "metode get_supported_file_types"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengambil tipe file yang didukung."
type: docs
url: /id/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Mengambil tipe file yang didukung.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Contoh

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### Lihat Juga
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
