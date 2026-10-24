---
title: "método from_extension"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Mapea la extensión de archivo al tipo de archivo."
type: docs
url: /es/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Mapea la extensión de archivo al tipo de archivo.

```python
def from_extension(cls, extension):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extension | `str` | Extensión de archivo (incluyendo el punto "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se produce cuando `extension` es nulo o una cadena vacía. |

### Ejemplo

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### Ver también
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
