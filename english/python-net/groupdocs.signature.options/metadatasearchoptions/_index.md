---
title: MetadataSearchOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 220
---

## MetadataSearchOptions class

Represents search options for Metadata signatures.



**Inheritance:** [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions) → 
[`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)



The MetadataSearchOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/#) | Initializes a new instance of the MetadataSearchOptions class with default values. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/page_number) | Gets or sets Document page number for searching.<br/>Value is optional. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/pages_setup) | Options to specify pages for Signature searching. |
| [all_pages](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/all_pages) | Flag to search on each Document page. By default this value is set to true. |
| [skip_external](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/skip_external) | Flag to return only signatures marked as IsSignature. By default value is false that indicates to return all signatures that match specified criteria. |
| [shape_position](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/shape_position) | Flag to return specify shape position in the document layout. Avaliable only for Word documents |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name) | Specifies Metadata Signature name if it should be searched and matched. |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type) | Gets or sets Metadata name Match Type search. It is used only when Name property is set. |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties) | Indicates if Built-in document properties like Document statistic, information etc should be included into Search result.<br/>This flag has sense for Presentation, Spreadsheet and Word Processing document file types. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption) | Gets or sets implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption) interface to decrypt all Metadata signatures withing this options collection.<br/>If this value is set all found signatures will use this encryption by default or its own DataEncryption if it was assigned. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions)
* class [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions)
