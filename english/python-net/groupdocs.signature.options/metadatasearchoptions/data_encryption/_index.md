﻿---
title: data_encryption property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/
is_root: false
weight: 40
---

## data_encryption property


Gets or sets implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption) interface to decrypt all Metadata signatures withing this options collection.
If this value is set all found signatures will use this encryption by default or its own DataEncryption if it was assigned.
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
* module [`groupdocs.signature.options`](../../)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions)
