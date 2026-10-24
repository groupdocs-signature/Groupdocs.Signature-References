---
title: "metoden get_document_info"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Hämtar information om dokumentsidor: deras storlekar, maximal sidhöjd, bredden på en sida med maximal höjd."
type: docs
url: /sv/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Hämtar information om dokumentsidor: deras storlekar, maximal sidhöjd, bredden på en sida med maximal höjd.

Läs mer om signerade dokument - filtyp, sidantal och många andra format‑specifika egenskaper:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Exempel

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number är 0‑baserad: 0 är den första sidan
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### Se även
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
