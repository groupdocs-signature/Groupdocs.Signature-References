---
title: "clone-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Klont die FormFieldSignature-Instanz."
type: docs
url: /de/python-net/groupdocs.signature.domain/textformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Klont die FormFieldSignature-Instanz.

```python
def clone(self):
    ...
```

**Returns:** TextFormFieldSignature: Cloned FormField Signature instance.

### Beispiel

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    new_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Siehe auch
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
