---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new PresentationSaveOptions instance with default values."
type: docs
url: /python-net/groupdocs.signature.options/presentationsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new PresentationSaveOptions instance with default values.

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

Initializes a new instance of PresentationSaveOptions with the specified output file format.

```python
def __init__(self, file_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_format | `PresentationSaveFileFormat` | Output file type. |

## __init__ {#overwrite_existing_file}

Initializes a new instance of PresentationSaveOptions with the specified output type and overwrite flag.

```python
def __init__(self, overwrite_existing_file):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| overwrite_existing_file | `bool` | Flag whether to overwrite signed file with same file. |

## __init__ {#file_format-overwrite_existing_file}

Initializes a new instance of PresentationSaveOptions with the specified output file format and overwrite flag.

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_format | `PresentationSaveFileFormat` | Output file type `PresentationSaveFileFormat`. |
| overwrite_existing_file | `bool` | Flag indicating whether to overwrite an existing signed file. |

### See Also
* class [`PresentationSaveOptions`](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/)
