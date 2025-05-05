---
title: ExportImageSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 120
---

## ExportImageSaveOptions class

Save options for exporting documents to image.



**Inheritance:** [`ExportImageSaveOptions`](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions) → 
[`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions) → 
[`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)



The ExportImageSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#) | Initializes a new instance of ExportAsImageSaveOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#groupdocs.signature.domain.ImageSaveFileFormat) | Initializes a new instance of ExportAsImageSaveOptions class with specified file format. |


### Properties
| Property | Description |
| :- | :- |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/overwrite_existing_files) | Gets or sets whether to overwrite existing file with new output file. <br/>Otherwise new file will be created with number as suffix.<br/>By default this value set to true that means file will be overwritten. |
| [password](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/password) | Gets or sets password to save signed document with password protection.<br/>This property is not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/use_original_password) | Gets or sets whether to use password from LoadOptions to save signed document as protected.<br/>Default value is true.<br/>This property is not supported for Image documents. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/add_missing_extenstion) | Gets or sets flag to automatically add extension when it was missing in output file path<br/>Default value is false. |
| [file_format](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/file_format) | Gets or sets file format of signed document. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number) | Gets or sets document page number for export.<br/>Minimal value is 1. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages) | Flag to export each page. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup) | Options to specify pages to be signed. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns) | Gets or sets number of columns for exported images. <br/>Use this property if you need put images in a row. |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border) | Gets or sets the image border settings. By default this value is not set. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage) | Put document pages on different frames in Tiff image. |



### See Also
* module [`groupdocs.signature.options`](..)
* class [`ExportImageSaveOptions`](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions)
* class [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
