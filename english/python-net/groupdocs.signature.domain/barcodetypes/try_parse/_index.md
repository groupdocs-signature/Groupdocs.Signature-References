---
title: try_parse method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Returns the Barcode type matching the given parsing type name."
type: docs
url: /python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Returns the Barcode type matching the given parsing type name.

If the name is unknown, the method returns None instead of raising an exception.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| parsing_type | `str` | Source string of barcode type name. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### See Also
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
