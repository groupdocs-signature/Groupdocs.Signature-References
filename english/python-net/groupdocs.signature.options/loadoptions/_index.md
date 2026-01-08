---
title: LoadOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 230
---

## LoadOptions class

Allows to specify additional options (such as password) when opening a document to sign.



The LoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#) | Initializes a new instance of LoadOptions class. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#groupdocs.signature.domain.FileType) | Initializes a new instance of the [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions) class with a specified file type. |


### Properties
| Property | Description |
| :- | :- |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password) | Gets or sets password to open a protected document.<br/>It will be also used to save signed document as protected. |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources) | Gets or sets options that specifies if external document resources should be loaded.<br/>This option with disabled value (false) allows to save loading time for the documents with many or large external resource links.<br/>By default value is enabled (true). |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions) | The PDF document permissions such as printing, modification and data extraction.Only for PDF documents. |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type) | Gets or sets the file type associated with the load options. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions)
