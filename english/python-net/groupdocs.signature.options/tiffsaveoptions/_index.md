---
title: TiffSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/tiffsaveoptions/
is_root: false
weight: 450
---

## TiffSaveOptions class

Tiff Save options for image documents.



**Inheritance:** [`TiffSaveOptions`](/signature/python-net/groupdocs.signature.options/tiffsaveoptions) → 
[`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions) → 
[`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)



The TiffSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/tiffsaveoptions/__init__/#) | Creates TiffSaveOptions with default values. |


### Properties
| Property | Description |
| :- | :- |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/tiffsaveoptions/overwrite_existing_files) | Gets or sets whether to overwrite existing file with new output file. <br/>Otherwise new file will be created with number as suffix.<br/>By default this value set to true that means file will be overwritten. |
| [password](/signature/python-net/groupdocs.signature.options/tiffsaveoptions/password) | Gets or sets password to save signed document with password protection.<br/>This property is not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/tiffsaveoptions/use_original_password) | Gets or sets whether to use password from LoadOptions to save signed document as protected.<br/>Default value is true.<br/>This property is not supported for Image documents. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/tiffsaveoptions/add_missing_extenstion) | Gets or sets flag to automatically add extension when it was missing in output file path<br/>Default value is false. |
| [file_format](/signature/python-net/groupdocs.signature.options/tiffsaveoptions/file_format) | Gets or sets file format of signed document. |
| [expected_tiff_format](/signature/python-net/groupdocs.signature.options/tiffsaveoptions/expected_tiff_format) | Gets or sets TIFF format of signed document. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
* class [`TiffSaveOptions`](/signature/python-net/groupdocs.signature.options/tiffsaveoptions)
