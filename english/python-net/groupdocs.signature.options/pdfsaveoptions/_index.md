---
title: PdfSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 250
---

## PdfSaveOptions class

Save options for PDF documents.



**Inheritance:** [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions) → 
[`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)



The PdfSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#) | Initializes a new instance of PdfSaveOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#groupdocs.signature.domain.PdfSaveFileFormat) | Initializes a new instance of PdfSaveOptions class with specified output file format. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#bool) | Initializes a new instance of PdfSaveOptions class with overwrite flag. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#groupdocs.signature.domain.PdfSaveFileFormat-bool) | Initializes a new instance of PdfSaveOptions class with specified output file format and overwrite flag. |


### Properties
| Property | Description |
| :- | :- |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/overwrite_existing_files) | Gets or sets whether to overwrite existing file with new output file. <br/>Otherwise new file will be created with number as suffix.<br/>By default this value set to true that means file will be overwritten. |
| [password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/password) | Gets or sets password to save signed document with password protection.<br/>This property is not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/use_original_password) | Gets or sets whether to use password from LoadOptions to save signed document as protected.<br/>Default value is true.<br/>This property is not supported for Image documents. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/add_missing_extenstion) | Gets or sets flag to automatically add extension when it was missing in output file path<br/>Default value is false. |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format) | Gets or sets file format of signed document. |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password) | A permissions password (the primary password) requires a password to change permission settings. |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions) | The PDF document permissions such as printing, modification and data extraction. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
