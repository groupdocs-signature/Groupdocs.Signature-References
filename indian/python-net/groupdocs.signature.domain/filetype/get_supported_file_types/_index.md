---
title: "\"get_supported_file_types मेथड\""
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "समर्थित फ़ाइल प्रकारों को प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

समर्थित फ़ाइल प्रकारों को प्राप्त करता है।

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### उदाहरण

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### संबंधित देखें
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
