---
title: DigitalSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 90
---

## DigitalSearchOptions class

Represents search options for Digital signatures.



**Inheritance:** [`DigitalSearchOptions`](/signature/python-net/groupdocs.signature.options/digitalsearchoptions) → 
[`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)



The DigitalSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/#) | Initializes a new instance of the DigitalSearchOptions class with default values. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/page_number) | Gets or sets Document page number for searching.<br/>Value is optional. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/pages_setup) | Options to specify pages for Signature searching. |
| [all_pages](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/all_pages) | Flag to search on each Document page. By default this value is set to true. |
| [skip_external](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/skip_external) | Flag to return only signatures marked as IsSignature. By default value is false that indicates to return all signatures that match specified criteria. |
| [shape_position](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/shape_position) | Flag to return specify shape position in the document layout. Avaliable only for Word documents |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments) | Comments of Digital signature to search. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from) | Date and time range of Digital signature to search. Nullable value will be ignored. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to) | Date and time range of Digital signature to search. Nullable value will be ignored. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name) | For non empty values specifies distinguished subject name of the certificate to search. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name) | For non empty values specifies distinguished name of the certificate issuer to search. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`DigitalSearchOptions`](/signature/python-net/groupdocs.signature.options/digitalsearchoptions)
* class [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)
