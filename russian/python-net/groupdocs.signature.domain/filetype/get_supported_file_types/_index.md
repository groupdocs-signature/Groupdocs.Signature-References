---
title: "метод get_supported_file_types"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Получает поддерживаемые типы файлов."
type: docs
url: /ru/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Получает поддерживаемые типы файлов.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### Пример

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### См. также
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
