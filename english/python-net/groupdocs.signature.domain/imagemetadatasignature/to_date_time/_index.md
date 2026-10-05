---
title: to_date_time method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Converts the metadata signature value to a datetime.datetime."
type: docs
url: /python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Converts the metadata signature value to a `datetime.datetime`.

Raises an exception if the metadata value cannot be converted. If the original value is string‑based, the default culture from [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) is used.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Converts the metadata signature value to a `datetime`.

Throws an exception if the metadata value could not be converted.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format data provider to use with data conversion operations. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### See Also
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
