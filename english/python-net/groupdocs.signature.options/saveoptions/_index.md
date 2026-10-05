---
title: SaveOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Specifies additional options (such as password) when saving a document to sign."
type: docs
url: /python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

Specifies additional options (such as password) when saving a document to sign.

The SaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | Initializes a new instance of SaveOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | Initializes a new instance of SaveOptions class with specified output type and overwrite flag. |

### Properties
| Property | Description |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | The flag that determines whether to automatically add an extension when it is missing in the output file path. Default value is False. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | The flag indicating whether to overwrite an existing file with the new output file. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | The password used to protect the saved signed document. Not supported for Image documents. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | The flag indicating whether to use the password from [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) when saving the signed document as protected. The default value is True. Not supported for Image documents. |

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
