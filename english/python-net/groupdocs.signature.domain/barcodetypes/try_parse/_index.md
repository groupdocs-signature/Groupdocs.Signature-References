---
title: try_parse method
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 30
---

## try_parse {#System.String}

Returns Barcode type with pasringType name. If name of Barcode is unknown - 
no Exception will be thrown but method will return null value.


### Returns 


BarcodeType instance.


```python
def try_parse(self, parsing_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| parsing_type | System.String | Source string of barcode type name. |



### See Also
* module [`groupdocs.signature.domain`](../../)
* class [`BarcodeType`](/signature/python-net/groupdocs.signature.domain/barcodetype)
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes)
