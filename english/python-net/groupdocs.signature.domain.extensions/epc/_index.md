---
title: EPC class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain.extensions/epc/
is_root: false
weight: 50
---

## EPC class

Represents European Payments Council Quick Response Code.



The EPC type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/epc/__init__/#) | Instantiates new EPC object. |


### Properties
| Property | Description |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/epc/name) | Gets or sets Beneficiary's Name. Maximum length is 70 characters. |
| [bic](/signature/python-net/groupdocs.signature.domain.extensions/epc/bic) | Gets or sets Beneficiary's BIC with up to 11 characters length. |
| [iban](/signature/python-net/groupdocs.signature.domain.extensions/epc/iban) | Gets or sets Beneficiary's Account (IBAN). The IBAN consists of up to 34 alphanumeric characters. |
| [amount](/signature/python-net/groupdocs.signature.domain.extensions/epc/amount) | Gets or sets amount. |
| [code](/signature/python-net/groupdocs.signature.domain.extensions/epc/code) | Gets or sets Business Code up to 4 characters. |
| [reference](/signature/python-net/groupdocs.signature.domain.extensions/epc/reference) | Gets or sets Payment Reference (maximum 35 characters). This field and the Remittance Information field are mutually exclusive. |
| [remittance](/signature/python-net/groupdocs.signature.domain.extensions/epc/remittance) | Gets or sets Remittance Information (maximum 140 characters). This field and the Payment Reference field are mutually exclusive. |
| [information](/signature/python-net/groupdocs.signature.domain.extensions/epc/information) | Gets or sets hint information. Maximum 70 characters. |
| [version](/signature/python-net/groupdocs.signature.domain.extensions/epc/version) | EPC / SEPA QR-Code version implementation. By default this value set to 002. |
| [charset](/signature/python-net/groupdocs.signature.domain.extensions/epc/charset) | EPC / SEPA QR-Code char set implementation. By default this value set to 1 |
| [identification](/signature/python-net/groupdocs.signature.domain.extensions/epc/identification) | EPC / SEPA QR-Code identification. By default this value set to SCT |



### See Also
* module [`groupdocs.signature.domain.extensions`](..)
