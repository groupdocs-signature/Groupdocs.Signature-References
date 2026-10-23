---
title: "طريقة get_supported_file_types"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يسترجع أنواع الملفات المدعومة."
type: docs
url: /ar/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

يسترجع أنواع الملفات المدعومة.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### مثال

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### انظر أيضًا
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
