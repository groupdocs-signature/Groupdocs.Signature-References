---
title: SwissAddress class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents the address of the creditor or debtor."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

Represents the address of the creditor or debtor.

You can either set street, house number, postal code, and town (structured address type) or address line 1 and 2 (combined address elements type).

The SwissAddress type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### Properties
| Property | Description |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | The address line 1, containing street name, house number, or P.O. box, is optional and used only for combined elements addresses. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | The address line 2, which contains the postal code and town, is mandatory for combined elements addresses. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | The two-letter ISO country code. The country code is mandatory unless the entire address contains null or empty values. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | The house number. This field is only used for structured addresses and is optional. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | The name, either the first and last name of a natural person or the company name of a legal person. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | The postal code. This field is only used for structured addresses. For this type, it's mandatory. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | The street of the address, without a house number; optional and used only for structured addresses. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | The town or city, used only for structured addresses and mandatory for this type. |

### See Also
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
