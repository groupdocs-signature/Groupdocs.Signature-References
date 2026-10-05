---
title: save_document_on_empty_delete property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag that determines whether the source document is re-saved when the Delete method has no affected signatures to remove."
type: docs
url: /python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 2050
---


## save_document_on_empty_delete property

The flag that determines whether the source document is re-saved when the Delete method has no affected signatures to remove.

When True (default), the document is saved with a history log (date and operation type) even if no signatures were removed; when False, the source document is left unchanged.

### Definition:
```python
@property
def save_document_on_empty_delete(self):
    ...
@save_document_on_empty_delete.setter
def save_document_on_empty_delete(self, value):
    ...
```

### See Also
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
