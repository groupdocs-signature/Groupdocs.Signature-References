---
title: save_document_on_empty_delete property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/
is_root: false
weight: 60
---

## save_document_on_empty_delete property


Gets or sets flag to re-save source document when Delete method has no affected signatures to remove.
If this flag is set to true (by default) document will be saving with corresponding history process log (date and operation type) even if Delete method has no signatures to remove.
When this flat is set to false source document will not be modified at all.
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
* module [`groupdocs.signature`](../../)
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings)
