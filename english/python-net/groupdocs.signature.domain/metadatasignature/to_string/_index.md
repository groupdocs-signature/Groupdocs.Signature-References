---
title: to_string method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Converts the metadata signature to a string."
type: docs
url: /python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

Converts the metadata signature to a string.

Converts a boolean property into "True" or "False". For other data types the default data format provider will be used.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

Converts the metadata signature to a string using the specified format.

Converts a boolean property into "True" or "False". Default culture property info will be used from SignatureSettings properties [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/).

```python
def to_string(self, format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| format | `str` | Data format string. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Converts to string with specified format.

Converts a boolean property into "True" or "False".

```python
def to_string(self, format, provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| format | `str` | Data format string. |
| provider | `System.IFormatProvider` | Format data provider to use with data conversion operations. |

**Returns:** The metadata signature value as a string.

### See Also
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
