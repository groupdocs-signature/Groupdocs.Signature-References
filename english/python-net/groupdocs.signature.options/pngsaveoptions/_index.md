---
title: PngSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "The PNG save options for image documents."
type: docs
url: /python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 400
---


## PngSaveOptions class

The PNG save options for image documents.

The PngSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/) | Initializes PngSaveOptions with default values. |

### Properties
| Property | Description |
| :- | :- |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth/) | The bit depth. |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type/) | The type of the `PngColorType`. |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level/) | The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode. |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type/) | The filter type `PngFilterType` used during PNG file save process. |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive/) | The progressive flag indicating whether the PNG is saved progressively. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | The flag that determines whether to automatically add an extension when it is missing in the output file path. Default value is False. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | The file format of the signed document. (inherited from [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | The flag indicating whether to overwrite an existing file with the new output file. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | The password used to protect the saved signed document. Not supported for Image documents. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | The flag indicating whether to use the password from [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) when saving the signed document as protected. The default value is True. Not supported for Image documents. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
