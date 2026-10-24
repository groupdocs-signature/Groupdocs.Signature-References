---
title: "clone método"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Clonar instancia de Metadata Signature."
type: docs
url: /es/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Clonar instancia de Metadata Signature.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Ejemplo

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Clonar una firma de metadatos estándar con un nuevo valor
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Clona una instancia de firma de metadatos PDF con el valor proporcionado.

```python
def clone(self, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | `Any` | Valor para el nuevo objeto clonado. |

**Returns:** A cloned metadata signature instance.

### Ejemplo

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Clonar una firma de metadatos existente con un nuevo valor
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Ver también
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
