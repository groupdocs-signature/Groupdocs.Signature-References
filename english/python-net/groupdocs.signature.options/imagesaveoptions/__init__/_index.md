---
title: ImageSaveOptions constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/imagesaveoptions/__init__/
is_root: false
weight: 10
---

## __init__ {#}

Initializes a new instance of ImagesSaveOptions class with default values.



```python
def __init__(self):
    ...
```




## __init__ {#bool}

Initializes a new instance of ImagesSaveOptions class with overwrite flag.



```python
def __init__(self, overwrite_existing_file):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| overwrite_existing_file | bool | Flag whether to overwrite signed file with same file. |


## __init__ {#groupdocs.signature.domain.ImageSaveFileFormat-bool}

Initializes a new instance of ImagesSaveOptions class with specified output type and overwrite flag.



```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_format | groupdocs.signature.domain.ImageSaveFileFormat | Output file type [`ImageSaveFileFormat`](/signature/python-net/groupdocs.signature.domain/imagesavefileformat). |
| overwrite_existing_file | bool | Flag whether to overwrite signed file with same file. |



### See Also
* module [`groupdocs.signature.options`](../../)
* class [`ImageSaveFileFormat`](/signature/python-net/groupdocs.signature.domain/imagesavefileformat)
* class [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions)
