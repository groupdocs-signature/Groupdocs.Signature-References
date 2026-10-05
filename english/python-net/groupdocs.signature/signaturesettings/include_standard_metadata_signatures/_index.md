---
title: include_standard_metadata_signatures property
second_title: GroupDocs.Signature for Python via .NET API References
description: "The flag indicating whether standard document metadata signatures such as Author, Owner, creation date, and modified date are included in the metadata list."
type: docs
url: /python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 2020
---


## include_standard_metadata_signatures property

The flag indicating whether standard document metadata signatures such as Author, Owner, creation date, and modified date are included in the metadata list.

If set to False (default), GetDocumentInfo will not include these metadata signatures. When set to True, the document information will include the standard metadata signatures.

### Definition:
```python
@property
def include_standard_metadata_signatures(self):
    ...
@include_standard_metadata_signatures.setter
def include_standard_metadata_signatures(self, value):
    ...
```

### See Also
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
