---
title: to_double method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Converts the metadata signature value to a float."
type: docs
url: /python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Converts the metadata signature value to a float.

Raises an exception if the metadata value cannot be converted. If the original value is string based, the default culture from [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) is used.

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Converts to Double.

```python
def to_double(self, provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format data provider to use with data conversion operations. |

**Returns:** float: The metadata signature value as a float.

### See Also
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
