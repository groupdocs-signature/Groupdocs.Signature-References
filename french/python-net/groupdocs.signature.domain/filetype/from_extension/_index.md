---
title: "méthode from_extension"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Mappe l'extension de fichier au type de fichier."
type: docs
url: /fr/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Mappe l'extension de fichier au type de fichier.

```python
def from_extension(cls, extension):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| extension | `str` | Extension de fichier (y compris le point "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Lève | Description |
| :- | :- |
| `ValueError` | Levée lorsque `extension` est nul ou une chaîne vide. |

### Exemple

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### Voir aussi
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
