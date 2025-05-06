---
title: SwissAddress class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 270
---

## SwissAddress class

Represents the address of the creditor or debtor.
You can either set street, house number, postal code, and town (structured address type)
or address line 1 and 2 (combined address elements type).



The SwissAddress type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/#) | Constructs a new instance of SwissAddress |


### Properties
| Property | Description |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name) | Gets or sets the name, either the first and last name of a natural person or<br/>the company name of a legal person. |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1) | Gets or sets the address line 1.<br/>Address line 1 contains street name, house number or P.O. box.<br/>This field is only used for combined elements addresses and is optional. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2) | Gets or sets the address line 2.<br/>Address line 2 contains postal code and town.<br/>This field is only used for combined elements addresses. For this type, it's mandatory. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street) | Gets or sets the street.<br/>The street must be specified without a house number.<br/>This field is only used for structured addresses and is optional. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no) | Gets or sets the house number.<br/>This field is only used for structured addresses and is optional. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code) | Gets or sets the postal code.<br/>This field is only used for structured addresses. For this type, it's mandatory. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town) | Gets or sets the town or city.<br/>This field is only used for structured addresses. For this type, it's mandatory. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code) | Gets or sets the two-letter ISO country code.<br/>The country code is mandatory unless the entire address contains null or empty values. |



### See Also
* module [`groupdocs.signature.domain.extensions`](..)
