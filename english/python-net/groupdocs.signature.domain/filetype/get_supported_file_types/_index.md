---
title: get_supported_file_types method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Retrieves supported file types."
type: docs
url: /python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Retrieves supported file types.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Example

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### See Also
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
