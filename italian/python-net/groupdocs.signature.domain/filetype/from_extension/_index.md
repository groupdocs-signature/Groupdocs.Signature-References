---
title: "metodo from_extension"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Mappa l'estensione del file al tipo di file."
type: docs
url: /it/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Mappa l'estensione del file al tipo di file.

```python
def from_extension(cls, extension):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extension | `str` | Estensione del file (incluso il punto "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Genera | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `extension` è nullo o una stringa vuota. |

### Esempio

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### Vedi anche
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
