---
title: JpegSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents JPEG save options for image documents."
type: docs
url: /python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

Represents JPEG save options for image documents.

The JpegSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | Initializes JpegSaveOptions with default values. |

### Properties
| Property | Description |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | The number of bits per channel for a lossless JPEG image. Supported values are from 2 to 8 bits per channel. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | The color type for JPEG image. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | The JPEG file comment. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | The compression type. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | The image quality. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | The sample rounding mode used to fit an 8-bit value to an n-bit value of `JpegOptions.BitsPerChannel`. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | The flag that determines whether to automatically add an extension when it is missing in the output file path. Default value is False. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | The file format of the signed document. (inherited from [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | The flag indicating whether to overwrite an existing file with the new output file. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | The password used to protect the saved signed document. Not supported for Image documents. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | The flag indicating whether to use the password from [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) when saving the signed document as protected. The default value is True. Not supported for Image documents. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
