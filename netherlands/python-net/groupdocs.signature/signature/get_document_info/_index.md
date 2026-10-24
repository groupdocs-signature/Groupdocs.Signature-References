---
title: "get_document_info methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Haalt informatie op over documentpagina's: hun afmetingen, maximale paginahoogte, de breedte van een pagina met de maximale hoogte."
type: docs
url: /nl/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Haalt informatie op over documentpagina's: hun afmetingen, maximale paginahoogte, de breedte van een pagina met de maximale hoogte.

Meer informatie over ondertekend document - bestandstype, aantal pagina's en vele andere formatspecifieke eigenschappen:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Voorbeeld

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number is 0-gebaseerd: 0 is de eerste pagina
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### Zie ook
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
