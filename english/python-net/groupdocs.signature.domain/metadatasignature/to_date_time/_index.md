---
title: to_date_time method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Converts the metadata signature value to a datetime."
type: docs
url: /python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Converts the metadata signature value to a datetime.

If the metadata value cannot be converted, an exception is raised. When the original value is string‑based, the default culture from [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) is used for conversion.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Converts the metadata signature value to a datetime.

```python
def to_date_time(self, provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Format data provider to use with data conversion operations. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Throws an exception if the metadata value could not be converted.

### See Also
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
