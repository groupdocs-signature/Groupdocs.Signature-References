---
title: BmpSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 40
---

## BmpSaveOptions class

Bmp Save options for image documents.



**Inheritance:** [`BmpSaveOptions`](/signature/python-net/groupdocs.signature.options/bmpsaveoptions) → 
[`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions) → 
[`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)



The BmpSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/#) | Creates BmpSaveOptions with default values. |


### Properties
| Property | Description |
| :- | :- |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/overwrite_existing_files) | Gets or sets whether to overwrite existing file with new output file. <br/>Otherwise new file will be created with number as suffix.<br/>By default this value set to true that means file will be overwritten. |
| [password](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/password) | Gets or sets password to save signed document with password protection.<br/>This property is not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/use_original_password) | Gets or sets whether to use password from LoadOptions to save signed document as protected.<br/>Default value is true.<br/>This property is not supported for Image documents. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/add_missing_extenstion) | Gets or sets flag to automatically add extension when it was missing in output file path<br/>Default value is false. |
| [file_format](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/file_format) | Gets or sets file format of signed document. |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel) | Gets or sets the image bits per pixel count. |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression) | Gets or sets the compression. See [`BitmapCompression`](/signature/python-net/groupdocs.signature.options/bitmapcompression). |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution) | Gets or sets the horizontal resolution. Note due to the rounding the resulting<br/>resolution may slightly differ from the passed. |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution) | Gets or sets the vertical resolution. Note due to the rounding the resulting<br/>resolution may slightly differ from the passed. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`BitmapCompression`](/signature/python-net/groupdocs.signature.options/bitmapcompression)
* class [`BmpSaveOptions`](/signature/python-net/groupdocs.signature.options/bmpsaveoptions)
* class [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
