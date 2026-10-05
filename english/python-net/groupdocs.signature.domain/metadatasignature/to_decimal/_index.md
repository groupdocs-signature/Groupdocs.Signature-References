---
title: to_decimal method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Converts the metadata signature value to Decimal."
type: docs
url: /python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Converts the metadata signature value to Decimal.

Raises an exception if the metadata value could not be converted. If the original value is string based, the default culture property info will be used from [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Converts the metadata signature value to a Decimal.

```python
def to_decimal(self, provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format data provider to use with data conversion operations. |

**Returns:** The metadata signature value as Decimal.

### See Also
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
