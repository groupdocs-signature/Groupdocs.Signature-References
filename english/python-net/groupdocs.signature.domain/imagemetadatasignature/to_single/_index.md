---
title: to_single method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Converts to float."
type: docs
url: /python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Converts to float.

Throws an exception if the Metadata value could not be converted. If the original value is string based, the default culture property info will be used from [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Converts the metadata signature value to a float.

Raises an exception if the metadata value could not be converted.

```python
def to_single(self, provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format data provider to use with data conversion operations. |

**Returns:** float: The metadata signature value as a float.

### See Also
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
