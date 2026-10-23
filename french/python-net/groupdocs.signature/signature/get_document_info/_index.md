---
title: "méthode get_document_info"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Obtient des informations sur les pages du document : leurs tailles, la hauteur maximale d'une page, la largeur d'une page avec la hauteur maximale."
type: docs
url: /fr/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

Obtient des informations sur les pages du document : leurs tailles, la hauteur maximale d'une page, la largeur d'une page avec la hauteur maximale.

En savoir plus sur le document signé - type de fichier, nombre de pages et de nombreuses autres propriétés spécifiques au format :
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### Exemple

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number est indexé à partir de 0 : 0 est la première page
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### Voir aussi
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
