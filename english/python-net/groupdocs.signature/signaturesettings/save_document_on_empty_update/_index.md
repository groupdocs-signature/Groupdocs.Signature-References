---
title: save_document_on_empty_update property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/
is_root: false
weight: 70
---

## save_document_on_empty_update property


Gets or sets flag to re-save source document when Update method has no signatures to update.
If this flag is set to true (by default) document will be saving with corresponding history process log (date and operation type) even if Update method has no signatures to update.
When this flat is set to false source document will not be modified at all.
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
* module [`groupdocs.signature`](../../)
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings)
