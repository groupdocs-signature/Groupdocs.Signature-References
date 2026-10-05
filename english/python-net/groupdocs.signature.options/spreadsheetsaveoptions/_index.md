---
title: SpreadsheetSaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents save options for spreadsheet documents."
type: docs
url: /python-net/groupdocs.signature.options/spreadsheetsaveoptions/
is_root: false
weight: 560
---


## SpreadsheetSaveOptions class

Represents save options for spreadsheet documents.

The SpreadsheetSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/spreadsheetsaveoptions/__init__/) | Initializes a new instance of SpreadsheetSaveOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/spreadsheetsaveoptions/__init__/#file_format) | Initializes a new instance of SpreadsheetSaveOptions with a predefined output file format. |
| [__init__](/signature/python-net/groupdocs.signature.options/spreadsheetsaveoptions/__init__/#file_format-overwrite_existing_file) | Initializes a new instance of SpreadsheetSaveOptions with the specified output file format and overwrite flag. |

### Properties
| Property | Description |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/spreadsheetsaveoptions/file_format/) | The file format of the signed document. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | The flag that determines whether to automatically add an extension when it is missing in the output file path. Default value is False. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | The flag indicating whether to overwrite an existing file with the new output file. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | The password used to protect the saved signed document. Not supported for Image documents. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | The flag indicating whether to use the password from [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) when saving the signed document as protected. The default value is True. Not supported for Image documents. (inherited from [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
