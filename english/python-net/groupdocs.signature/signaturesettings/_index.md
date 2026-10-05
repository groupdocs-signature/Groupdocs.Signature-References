---
title: SignatureSettings class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents settings for customizing Signature behavior."
type: docs
url: /python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Represents settings for customizing [`Signature`](/signature/python-net/groupdocs.signature/signature/) behavior.

The SignatureSettings type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Initializes a default SignatureSettings instance with default values. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Initializes a default SignatureSettings instance with the Logger implementation. |

### Properties
| Property | Description |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | The default culture used during document processing. The default value is "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | The flag indicating whether standard document metadata signatures such as Author, Owner, creation date, and modified date are included in the metadata list. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | The log level flags that determine which kinds of messages are passed to [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | The logger implementation used for logging (Errors, Warnings, Traces). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | The flag that determines whether the source document is re-saved when the Delete method has no affected signatures to remove. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | The flag that determines whether the source document is re‑saved when the `Update` method has no signatures to update. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | The flag that determines whether deleted signatures are included in the document info result. Each [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) has a `Deleted` flag to indicate if it was deleted. |

### See Also
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
