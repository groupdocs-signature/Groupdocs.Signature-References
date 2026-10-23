---
title: "from_extension मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है।

```python
def from_extension(cls, extension):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| extension | `str` | File extension (including the period "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| उठाता है | विवरण |
| :- | :- |
| `ValueError` | जब `extension` null या खाली स्ट्रिंग हो तो उत्पन्न होता है। |

### उदाहरण

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### संबंधित देखें
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
