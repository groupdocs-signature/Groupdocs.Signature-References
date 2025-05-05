---
title: SignatureSettings class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 110
---

## SignatureSettings class

Defines settings for customizing [`Signature`](/signature/python-net/groupdocs.signature/signature) behavior.



The SignatureSettings type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#) | Creates default SignatureSettings instance with default values. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#groupdocs.signature.logging.ILogger) | Creates default SignatureSettings instance with the Logger implementation. |


### Properties
| Property | Description |
| :- | :- |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info) | Gets or sets flag that includes deleted signatures into Document Info result.<br/>Each Signature [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature) has Deleted flag [`BaseSignature.deleted`](/signature/python-net/groupdocs.signature.domain/basesignature#deleted) to detect if it was deleted. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update) | Gets or sets flag to re-save source document when Update method has no signatures to update.<br/>If this flag is set to true (by default) document will be saving with corresponding history process log (date and operation type) even if Update method has no signatures to update.<br/>When this flat is set to false source document will not be modified at all. |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete) | Gets or sets flag to re-save source document when Delete method has no affected signatures to remove.<br/>If this flag is set to true (by default) document will be saving with corresponding history process log (date and operation type) even if Delete method has no signatures to remove.<br/>When this flat is set to false source document will not be modified at all. |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures) | Gets or sets flag to include into the Metadata List the embedded standard document metadata signatures like Author, Owner, document creation date, modified date, etc.<br/>If this flag is set to false (by default) the GetDocumentInfo will not include these metadata signatures.<br/>When this flag is set to true the document information will include these standard metadata signatures. |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger) | The logger implementation used for logging (Errors, Warnings, Traces). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger). |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level) | The level of the logging to limit the messages (All, Traces, Warnings, Errors). [`SignatureSettings.log_level`](/signature/python-net/groupdocs.signature/signaturesettings#log_level).<br/>BY default the All level type is set. |



### See Also
* module [`groupdocs.signature`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger)
* class [`Signature`](/signature/python-net/groupdocs.signature/signature)
