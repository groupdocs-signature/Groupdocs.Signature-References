---
title: destination_post_code_and_dps property
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/
is_root: false
weight: 70
---

## destination_post_code_and_dps property


Contains the Postcode of the Delivery Address with DPS 
If inland the Postcode/DP  contains the following number of characters. 
Area (1 or 2 characters) 
District(1 or 2 characters)
Sector(1 character) 
Unit(2 characters) 
DPS (2 characters). 
The Postcode and DPS must comply with a valid PAF® format. Max length is 9.
### Definition:
```python
@property
def destination_post_code_and_dps(self):
    ...
@destination_post_code_and_dps.setter
def destination_post_code_and_dps(self, value):
    ...
```

### See Also
* module [`groupdocs.signature.domain.extensions`](../../)
* class [`Mailmark2D`](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d)
