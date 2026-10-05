---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a PDF metadata signature with a predefined name and an empty value."
type: docs
url: /python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initializes a PDF metadata signature with a predefined name and an empty value.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | PDF metadata signature name. |

## __init__ {#name-value}

Initializes a PDF metadata signature with predefined values.

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
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

Initializes a PDF metadata signature with predefined values.

```python
def __init__(self, name, value, tag):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | Name of the metadata signature object. |
| value | `Any` | Value of the metadata signature. |
| tag | `str` | Prefix tag of the metadata signature. |

### Example

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Create a metadata signature for the PDF author
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Create a metadata signature for the creation date
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Create a metadata signature for a numeric identifier
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Create a metadata signature for a floating‑point value
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### See Also
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
