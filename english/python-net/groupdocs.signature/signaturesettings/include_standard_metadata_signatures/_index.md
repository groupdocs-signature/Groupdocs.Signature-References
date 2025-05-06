---
title: include_standard_metadata_signatures property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/
is_root: false
weight: 30
---

## include_standard_metadata_signatures property


Gets or sets flag to include into the Metadata List the embedded standard document metadata signatures like Author, Owner, document creation date, modified date, etc.
If this flag is set to false (by default) the GetDocumentInfo will not include these metadata signatures.
When this flag is set to true the document information will include these standard metadata signatures.
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
* module [`groupdocs.signature`](../../)
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings)
