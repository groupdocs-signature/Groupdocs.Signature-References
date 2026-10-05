---
title: to_string method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Converts the metadata signature value to a string."
type: docs
url: /python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Converts the metadata signature value to a string.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Converts the metadata signature value to a string using the specified format.

Converts a boolean property into "True" or "False". The default culture information from [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) is used.

```python
def to_string(self, format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| format | `str` | Data format string. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Converts to a string with the specified format.

Converts a boolean property into "True" or "False".

```python
def to_string(self, format, provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| format | `str` | Data format string. |
| provider | `System.IFormatProvider` | Format data provider to use with data conversion operations. |

**Returns:** str: The metadata signature value as a string.

### See Also
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
