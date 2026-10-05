---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes Spreadsheet Metadata Signature with predefined name and empty value."
type: docs
url: /python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initializes Spreadsheet Metadata Signature with predefined name and empty value.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | Spreadsheet Metadata Signature name. |

## __init__ {#name-value}

Initializes a Spreadsheet Metadata Signature with predefined values.

```python
def __init__(self, name, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | Name of the metadata signature object. |
| value | `Any` | Value of the metadata signature. |

### Example

```python
from datetime import datetime
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Create metadata signatures for a spreadsheet
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### See Also
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
