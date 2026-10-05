---
title: LoadOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "The LoadOptions class allows specifying additional options (such as password) when opening a document to sign."
type: docs
url: /python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

The LoadOptions class allows specifying additional options (such as password) when opening a document to sign.

Set the `password` attribute to the document password if the file is encrypted.

The LoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | Initializes a new instance of LoadOptions class. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | Initializes a new instance of the [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) class with a specified file type. |

### Properties
| Property | Description |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | The file type associated with the load options, defaulting to [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | The flag that determines whether the document loads external resources. This property is obsolete; use [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) instead, which has the opposite meaning. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | The password used to open a protected document and to save a signed document as protected. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | The PDF document permissions such as printing, modification and data extraction. Only for PDF documents. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | The flag that stops the document from loading external resources. The default value is True; external resources are not loaded except those that match [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | The list of address fragments of external resources that are loaded even when [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) is true. The default value is an empty list. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
