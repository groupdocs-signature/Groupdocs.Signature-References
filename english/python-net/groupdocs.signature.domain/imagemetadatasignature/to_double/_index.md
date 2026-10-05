---
title: to_double method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Converts to a float."
type: docs
url: /python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Converts to a float.

Raises an exception if the metadata value cannot be converted. If the original value is string‑based, the default culture from [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) is used.

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Converts the metadata signature value to a float.

Uses the specified format data provider to perform the conversion.

```python
def to_double(self, provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format data provider to use with data conversion operations. |

**Returns:** float: The metadata signature value as a float.

### See Also
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
