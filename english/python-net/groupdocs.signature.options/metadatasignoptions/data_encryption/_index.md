---
title: data_encryption property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The implementation of IDataEncryption used to encrypt all metadata signatures in this options collection."
type: docs
url: /python-net/groupdocs.signature.options/metadatasignoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

The implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) used to encrypt all metadata signatures in this options collection.

If set, all added signatures will use this encryption by default unless they have their own DataEncryption assigned.

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### See Also
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
