---
title: JpegSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 200
---

## JpegSaveOptions class

Jpeg Save options for image documents.



**Inheritance:** [`JpegSaveOptions`](/signature/python-net/groupdocs.signature.options/jpegsaveoptions) → 
[`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions) → 
[`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)



The JpegSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/#) | Creates JpegSaveOptions with default values. |


### Properties
| Property | Description |
| :- | :- |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/overwrite_existing_files) | Gets or sets whether to overwrite existing file with new output file. <br/>Otherwise new file will be created with number as suffix.<br/>By default this value set to true that means file will be overwritten. |
| [password](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/password) | Gets or sets password to save signed document with password protection.<br/>This property is not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/use_original_password) | Gets or sets whether to use password from LoadOptions to save signed document as protected.<br/>Default value is true.<br/>This property is not supported for Image documents. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/add_missing_extenstion) | Gets or sets flag to automatically add extension when it was missing in output file path<br/>Default value is false. |
| [file_format](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/file_format) | Gets or sets file format of signed document. |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel) | Gets or sets bits per channel for lossless jpeg image. <br/>Now we support from 2 to 8 bits per channel. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type) | Gets or sets the color type for jpeg image. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment) | Gets or sets the jpeg file comment. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type) | Gets or sets the compression type. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality) | Gets or sets image quality. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode) | Gets or sets the sample rounding mode to fit an 8-bit value to an n-bit value<br/>JpegOptions.BitsPerChannel. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions)
* class [`JpegSaveOptions`](/signature/python-net/groupdocs.signature.options/jpegsaveoptions)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
