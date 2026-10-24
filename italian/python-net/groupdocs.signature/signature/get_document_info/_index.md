---
title: "metodo get_document_info"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima."
type: docs
url: /it/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima.

Scopri di più sul documento firmato - tipo di file, numero di pagine e molte altre proprietà specifiche del formato:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Esempio

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number è basato su zero: 0 è la prima pagina
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### Vedi anche
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
