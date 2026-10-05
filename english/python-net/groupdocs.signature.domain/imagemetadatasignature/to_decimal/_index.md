---
title: to_decimal method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Converts to Decimal."
type: docs
url: /python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Converts to Decimal.

Raises an exception if the metadata value cannot be converted. If the original value is string based, the default culture from [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) is used.

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Converts the metadata signature value to a decimal.

Raises an exception if the metadata value could not be converted.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format data provider to use with data conversion operations. |

**Returns:** float: The metadata signature value as a decimal.

### See Also
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
