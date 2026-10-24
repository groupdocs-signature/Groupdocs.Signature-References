---
title: "clone método"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Clona una instancia de firma de metadatos."
type: docs
url: /es/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Clona una instancia de firma de metadatos.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Ejemplo

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Crear una nueva firma de metadatos basada en la firma predefinida AUTHOR
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Clona una instancia de firma de metadatos con el valor dado.

```python
def clone(self, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | `Any` | Valor para el nuevo objeto clonado. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Ejemplo

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Clonar una firma de metadatos existente con un nuevo valor
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Ver también
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
