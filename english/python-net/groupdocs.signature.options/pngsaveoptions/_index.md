---
title: PngSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 300
---

## PngSaveOptions class

Png Save options for image documents.



**Inheritance:** [`PngSaveOptions`](/signature/python-net/groupdocs.signature.options/pngsaveoptions) → 
[`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions) → 
[`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)



The PngSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/#) | Creates PngSaveOptions with default values. |


### Properties
| Property | Description |
| :- | :- |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/pngsaveoptions/overwrite_existing_files) | Gets or sets whether to overwrite existing file with new output file. <br/>Otherwise new file will be created with number as suffix.<br/>By default this value set to true that means file will be overwritten. |
| [password](/signature/python-net/groupdocs.signature.options/pngsaveoptions/password) | Gets or sets password to save signed document with password protection.<br/>This property is not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/pngsaveoptions/use_original_password) | Gets or sets whether to use password from LoadOptions to save signed document as protected.<br/>Default value is true.<br/>This property is not supported for Image documents. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/pngsaveoptions/add_missing_extenstion) | Gets or sets flag to automatically add extension when it was missing in output file path<br/>Default value is false. |
| [file_format](/signature/python-net/groupdocs.signature.options/pngsaveoptions/file_format) | Gets or sets file format of signed document. |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth) | The bit depth. |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type) | Gets or sets the type of the [`PngColorType`](/signature/python-net/groupdocs.signature.options/pngcolortype). |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level) | The png image compression level in the 0-9 range, where 9 is maximum compression<br/>and 0 is store mode. |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type) | Gets or sets the filter type [`PngFilterType`](/signature/python-net/groupdocs.signature.options/pngfiltertype) used during png file save process. |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive) | Gets or sets a value indicating whether this PngSaveOptions is progressive. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions)
* class [`PngColorType`](/signature/python-net/groupdocs.signature.options/pngcolortype)
* class [`PngFilterType`](/signature/python-net/groupdocs.signature.options/pngfiltertype)
* class [`PngSaveOptions`](/signature/python-net/groupdocs.signature.options/pngsaveoptions)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
