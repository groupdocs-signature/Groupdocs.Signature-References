---
title: SwissQR class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/swissqr/
is_root: false
weight: 280
---

## SwissQR class

Class for encoding and decoding the text embedded in the SwissQR code.



The SwissQR type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/__init__/#) | Creates an instance of SwissQR. |


### Properties
| Property | Description |
| :- | :- |
| [amount](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/amount) | Gets or sets the payment amount.<br/>Valid values are between 0.01 and 999,999,999.99. |
| [currency](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/currency) | Gets or sets the payment currency.<br/>Valid values are "CHF" and "EUR". |
| [account](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/account) | Gets or sets the creditor's account number.<br/>Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein.<br/>Spaces are allowed in the account number. |
| [creditor](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/creditor) | Gets or sets the creditor address. |
| [reference](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/reference) | Gets or sets the creditor payment reference.<br/>The reference is mandatory for SwissQR IBANs, i.e. IBANs in the range CHxx30000xxxxxx<br/>through CHxx31999xxxxx.<br/>If specified, the reference must be either a valid SwissQR reference (corresponding<br/>to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx").<br/>Both may contain spaces for formatting. |
| [debtor](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/debtor) | Gets or sets the debtor address.<br/>The debtor is optional. If it is omitted, both setting this field to null or<br/>setting an address with all null or empty values is ok. |
| [unstructured_message](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/unstructured_message) | Gets or sets the additional unstructured message. |
| [bill_information](/signature/python-net/groupdocs.signature.domain.extensions/swissqr/bill_information) | Gets or sets the additional structured bill information. |



### See Also
* module [`groupdocs.signature.domain.extensions`](..)
