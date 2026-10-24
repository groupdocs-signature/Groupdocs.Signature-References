---
title: "metodo clone"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Clona un'istanza di Metadata Signature."
type: docs
url: /it/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Clona un'istanza di Metadata Signature.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Esempio

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Crea una nuova firma metadata basata sulla firma predefinita AUTHOR
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Clona l'istanza di Metadata Signature con il valore fornito.

```python
def clone(self, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | `Any` | Valore per il nuovo oggetto clonato. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Esempio

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Clona una firma di metadati esistente con un nuovo valore
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Vedi anche
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
