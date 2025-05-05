---
title: PresentationSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/presentationsaveoptions/
is_root: false
weight: 290
---

## PresentationSaveOptions class

Save options for Presentation documents.



**Inheritance:** [`PresentationSaveOptions`](/signature/python-net/groupdocs.signature.options/presentationsaveoptions) → 
[`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)



The PresentationSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/__init__/#) | Initializes a new instance of PresentationSaveOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/__init__/#groupdocs.signature.domain.PresentationSaveFileFormat) | Initializes a new instance of PresentationSaveOptions class with specified output file format. |
| [__init__](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/__init__/#bool) | Initializes a new instance of PresentationSaveOptions class with specified output type and overwrite flag. |
| [__init__](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/__init__/#groupdocs.signature.domain.PresentationSaveFileFormat-bool) | Initializes a new instance of PresentationSaveOptions class with specified output file format and overwrite flag. |


### Properties
| Property | Description |
| :- | :- |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/overwrite_existing_files) | Gets or sets whether to overwrite existing file with new output file. <br/>Otherwise new file will be created with number as suffix.<br/>By default this value set to true that means file will be overwritten. |
| [password](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/password) | Gets or sets password to save signed document with password protection.<br/>This property is not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/use_original_password) | Gets or sets whether to use password from LoadOptions to save signed document as protected.<br/>Default value is true.<br/>This property is not supported for Image documents. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/add_missing_extenstion) | Gets or sets flag to automatically add extension when it was missing in output file path<br/>Default value is false. |
| [file_format](/signature/python-net/groupdocs.signature.options/presentationsaveoptions/file_format) | Gets or sets file format of signed document. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`PresentationSaveOptions`](/signature/python-net/groupdocs.signature.options/presentationsaveoptions)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
