---
title: "metodo clone"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Clona l'istanza di Metadata Signature."
type: docs
url: /it/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Clona l'istanza di Metadata Signature.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Esempio

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Clona una firma di metadati standard con un nuovo valore
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Clona un'istanza di firma di metadati PDF con il valore fornito.

```python
def clone(self, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | `Any` | Valore per il nuovo oggetto clonato |

**Returns:** A cloned metadata signature instance.

### Esempio

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Clona una firma di metadati esistente con un nuovo valore
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Vedi anche
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
