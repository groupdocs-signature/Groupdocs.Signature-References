---
title: DigitalSignOptions constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---

## __init__ {#}

Initializes a new instance of the DigitalSignOptions class with default values.



```python
def __init__(self):
    ...
```




## __init__ {#str}

Initializes a new instance of the DigitalSignOptions class with certificate file.



```python
def __init__(self, certificate_file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| certificate_file_path | str | Digital certificate file path |


## __init__ {#io.RawIOBase}

Initializes a new instance of the DigitalSignOptions class with certificate stream.



```python
def __init__(self, certificate_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| certificate_stream | io.RawIOBase | Digital Certificate stream |


## __init__ {#str-str}

Initializes a new instance of the DigitalSignOptions class with certificate file and image file.



```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| certificate_file_path | str | Digital certificate file path |
| image_file_path | str | Signature Appearance image file path |


## __init__ {#str-io.RawIOBase}

Initializes a new instance of the DigitalSignOptions class with certificate file and image stream.



```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| certificate_file_path | str | Digital certificate file path |
| appearence_image_stream | io.RawIOBase | Signature Appearance image stream |


## __init__ {#io.RawIOBase-str}

Initializes a new instance of the DigitalSignOptions class with certificate stream and image file.



```python
def __init__(self, certificate_stream, image_file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| certificate_stream | io.RawIOBase | Digital Certificate stream |
| image_file_path | str | Signature Appearance image file path |


## __init__ {#io.RawIOBase-io.RawIOBase}

Initializes a new instance of the DigitalSignOptions class with certificate stream and image stream.



```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| certificate_stream | io.RawIOBase | Digital Certificate stream |
| appearence_image_stream | io.RawIOBase | Signature Appearance image stream |



### See Also
* module [`groupdocs.signature.options`](../../)
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions)
