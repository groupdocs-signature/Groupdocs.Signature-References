---
title: "get_document_info-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Ruft Informationen über Dokumentseiten ab: deren Größen, maximale Seitenhöhe, die Breite einer Seite mit der maximalen Höhe."
type: docs
url: /de/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Ruft Informationen über Dokumentseiten ab: deren Größen, maximale Seitenhöhe, die Breite einer Seite mit der maximalen Höhe.

Erfahren Sie mehr über das signierte Dokument – Dateityp, Seitenanzahl und viele weitere formatbezogene Eigenschaften:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Beispiel

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number ist 0-basiert: 0 ist die erste Seite
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### Siehe auch
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
