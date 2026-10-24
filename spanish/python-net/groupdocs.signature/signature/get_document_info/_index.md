---
title: "método get_document_info"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Obtiene información sobre las páginas del documento: sus tamaños, la altura máxima de página, el ancho de una página con la altura máxima."
type: docs
url: /es/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Obtiene información sobre las páginas del documento: sus tamaños, la altura máxima de página, el ancho de una página con la altura máxima.

Obtenga más información sobre el documento firmado: tipo de archivo, número de páginas y muchas otras propiedades específicas del formato:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Ejemplo

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number es indexado desde 0: 0 es la primera página
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### Ver también
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
