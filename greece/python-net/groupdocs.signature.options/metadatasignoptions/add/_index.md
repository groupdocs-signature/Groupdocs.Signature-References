---
title: "add μέθοδος"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Προσθέτει υπάρχον αντικείμενο MetadataSignature στη συλλογή."
type: docs
url: /el/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

Προσθέτει υπάρχον αντικείμενο MetadataSignature στη συλλογή.

```python
def add(self, metadata_signature):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | Η υπάρχουσα παρουσία του MetadataSignature που θα προστεθεί. |

**Returns:** The MetadataSignOptions instance.

### Παράδειγμα

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s)")
```

### Δείτε επίσης
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
