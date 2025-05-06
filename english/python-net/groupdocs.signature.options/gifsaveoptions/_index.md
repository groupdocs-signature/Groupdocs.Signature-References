---
title: GifSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/gifsaveoptions/
is_root: false
weight: 150
---

## GifSaveOptions class

Gif format save options for image documents.



**Inheritance:** [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions) → 
[`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions) → 
[`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)



The GifSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/gifsaveoptions/__init__/#) | Creates GifSaveOptions with default values. |


### Properties
| Property | Description |
| :- | :- |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/gifsaveoptions/overwrite_existing_files) | Gets or sets whether to overwrite existing file with new output file. <br/>Otherwise new file will be created with number as suffix.<br/>By default this value set to true that means file will be overwritten. |
| [password](/signature/python-net/groupdocs.signature.options/gifsaveoptions/password) | Gets or sets password to save signed document with password protection.<br/>This property is not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/gifsaveoptions/use_original_password) | Gets or sets whether to use password from LoadOptions to save signed document as protected.<br/>Default value is true.<br/>This property is not supported for Image documents. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/gifsaveoptions/add_missing_extenstion) | Gets or sets flag to automatically add extension when it was missing in output file path<br/>Default value is false. |
| [file_format](/signature/python-net/groupdocs.signature.options/gifsaveoptions/file_format) | Gets or sets file format of signed document. |
| [background_color_index](/signature/python-net/groupdocs.signature.options/gifsaveoptions/background_color_index) | Gets or sets the GIF background color index. |
| [color_resolution](/signature/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution) | Gets or sets the GIF color resolution. |
| [do_palette_correction](/signature/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction) | Gets or sets a value indicating whether palette correction is applied. |
| [has_trailer](/signature/python-net/groupdocs.signature.options/gifsaveoptions/has_trailer) | Gets or sets a value indicating whether GIF has trailer. |
| [interlaced](/signature/python-net/groupdocs.signature.options/gifsaveoptions/interlaced) | True if image should be interlaced. |
| [is_palette_sorted](/signature/python-net/groupdocs.signature.options/gifsaveoptions/is_palette_sorted) | Gets or sets a value indicating whether palette entries are sorted. |
| [pixel_aspect_ratio](/signature/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio) | Gets or sets the GIF pixel aspect ratio. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions)
* class [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
