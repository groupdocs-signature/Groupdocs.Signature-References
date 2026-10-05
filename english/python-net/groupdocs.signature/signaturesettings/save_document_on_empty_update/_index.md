---
title: save_document_on_empty_update property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag that determines whether the source document is re‑saved when the Update method has no signatures to update."
type: docs
url: /python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 2060
---


## save_document_on_empty_update property

The flag that determines whether the source document is re‑saved when the `Update` method has no signatures to update.

If set to `True` (default), the document is saved with a corresponding history process log (date and operation type) even when no signatures are updated. When set to `False`, the source document is not modified at all.

### Definition:
```python
@property
def save_document_on_empty_update(self):
    ...
@save_document_on_empty_update.setter
def save_document_on_empty_update(self, value):
    ...
```

### See Also
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
