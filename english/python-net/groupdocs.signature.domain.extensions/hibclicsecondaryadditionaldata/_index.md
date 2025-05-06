---
title: HIBCLICSecondaryAdditionalData class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/
is_root: false
weight: 110
---

## HIBCLICSecondaryAdditionalData class

Class for storing HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) secondary and additional data.



The HIBCLICSecondaryAdditionalData type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/__init__/#) | Default ctor() |


### Properties
| Property | Description |
| :- | :- |
| [expiry_date_format](/signature/python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/expiry_date_format) | Identifies expiry date format. |
| [expiry_date](/signature/python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/expiry_date) | Identifies expiry date. Will be used if ExpiryDateFormat is not set to None. |
| [lot_number](/signature/python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/lot_number) | Identifies lot or batch number. <br/>Lot/batch number must be alphanumeric string with up to 18 symbols length. |
| [serial_number](/signature/python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/serial_number) | Identifies serial number.<br/>Serial number must be alphanumeric string up to 18 symbols length. |
| [date_of_manufacture](/signature/python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/date_of_manufacture) | Identifies date of manufacture. <br/>Date of manufacture can be set to DateTime.MinValue in order not to use this field.<br/>Default value: DateTime.MinValue |
| [quantity](/signature/python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/quantity) | Identifies quantity, must be integer value from 0 to 500. <br/>Quantity can be set to -1 in order not to use this field. Default value: -1 |
| [link_character](/signature/python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/link_character) | Identifies link character in output string. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/hibclicsecondaryadditionaldata/clone/#) | Gets a copy of this object. |



### See Also
* module [`groupdocs.signature.domain.extensions`](..)
