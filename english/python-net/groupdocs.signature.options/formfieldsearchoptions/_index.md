---
title: FormFieldSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 130
---

## FormFieldSearchOptions class

Represents search options for Form-field signatures.



**Inheritance:** [`FormFieldSearchOptions`](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions) → 
[`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)



The FormFieldSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/#) | Initializes a new instance of the FormFieldSearchOptions class with default values. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/page_number) | Gets or sets Document page number for searching.<br/>Value is optional. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/pages_setup) | Options to specify pages for Signature searching. |
| [all_pages](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/all_pages) | Flag to search on each Document page. By default this value is set to true. |
| [skip_external](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/skip_external) | Flag to return only signatures marked as IsSignature. By default value is false that indicates to return all signatures that match specified criteria. |
| [shape_position](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/shape_position) | Flag to return specify shape position in the document layout. Avaliable only for Word documents |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type) | Specifies type of form field signature if it should be searched. Default value is null. |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name) | Specifies regular expression pattern of form field signature name if it should be searched. <br/>You can use it simple as "text" or regular expression like "abc\d+". Default value is empty string. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value) | Specifies value of form field signature if it should be searched. Default value is null. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`FormFieldSearchOptions`](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions)
* class [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)
