---
title: BmpSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents BMP save options for image documents."
type: docs
url: /python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 50
---


## BmpSaveOptions class

Represents BMP save options for image documents.

The BmpSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/) | Initializes BmpSaveOptions with default values. |

### Properties
| Property | Description |
| :- | :- |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel/) | The image bits per pixel count. |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression/) | The compression. See `BitmapCompression`. |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution/) | The horizontal resolution. Note that due to rounding the resulting resolution may slightly differ from the value set. |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution/) | The vertical resolution; note that due to rounding the resulting resolution may slightly differ from the value set. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | The flag that determines whether to automatically add an extension when it is missing in the output file path. Default value is False. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | The file format of the signed document. (inherited from [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | The flag indicating whether to overwrite an existing file with the new output file. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | The password used to protect the saved signed document. Not supported for Image documents. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | The flag indicating whether to use the password from [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) when saving the signed document as protected. The default value is True. Not supported for Image documents. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
