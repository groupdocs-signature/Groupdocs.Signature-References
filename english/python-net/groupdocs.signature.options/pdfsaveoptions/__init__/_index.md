---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of PdfSaveOptions with default values."
type: docs
url: /python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of PdfSaveOptions with default values.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Initializes a new instance of PdfSaveOptions with the specified output file format.

```python
def __init__(self, file_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Output file type `PdfSaveFileFormat`. |

## __init__ {#overwrite_existing_file}

Initializes a new instance of PdfSaveOptions with an overwrite flag.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Flag whether to overwrite signed file with same file. |

## __init__ {#file_format-overwrite_existing_file}

Initializes a new instance of PdfSaveOptions with the specified output file format and overwrite flag.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | Output file type. |
| overwrite_existing_file | `bool` | Flag whether to overwrite signed file with same file. |

### Example

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# Create save options with PDF format and allow overwriting existing files
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### See Also
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
