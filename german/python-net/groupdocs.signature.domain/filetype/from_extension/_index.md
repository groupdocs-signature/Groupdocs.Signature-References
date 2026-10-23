---
title: "from_extension-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Ordnet Dateierweiterungen dem Dateityp zu."
type: docs
url: /de/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Ordnet Dateierweiterungen dem Dateityp zu.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extension | `str` | Dateierweiterung (einschließlich des Punktes \".\"). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `extension` null oder ein leerer String ist. |

### Beispiel

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### Siehe auch
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
