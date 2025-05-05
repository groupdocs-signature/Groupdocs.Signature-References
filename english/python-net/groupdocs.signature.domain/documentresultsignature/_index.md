---
title: DocumentResultSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/documentresultsignature/
is_root: false
weight: 150
---

## DocumentResultSignature class

Result of processing archive document signing process for document with newly created signatures.



**Inheritance:** [`DocumentResultSignature`](/signature/python-net/groupdocs.signature.domain/documentresultsignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The DocumentResultSignature type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/documentresultsignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/documentresultsignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/documentresultsignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/documentresultsignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/documentresultsignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/documentresultsignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/documentresultsignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/documentresultsignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/documentresultsignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/documentresultsignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/documentresultsignature/height) | Specifies height of signature. |
| [file_name](/signature/python-net/groupdocs.signature.domain/documentresultsignature/file_name) | Document file name |
| [processing_time](/signature/python-net/groupdocs.signature.domain/documentresultsignature/processing_time) | Returns the execution time of the process in milliseconds |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/documentresultsignature/total_signatures) | Returns the total processed signatures |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/documentresultsignature/source_document_size) | Returns source document size |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/documentresultsignature/destin_document_size) | Returns destination document size |
| [succeeded](/signature/python-net/groupdocs.signature.domain/documentresultsignature/succeeded) | List of successfully processed signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature). |
| [failed](/signature/python-net/groupdocs.signature.domain/documentresultsignature/failed) | List of the signatures that failed during the process [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature). |
| [error_message](/signature/python-net/groupdocs.signature.domain/documentresultsignature/error_message) | if document was processed with error this property will contain the error message |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/documentresultsignature/clone/#) | Clone signature instance. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`DocumentResultSignature`](/signature/python-net/groupdocs.signature.domain/documentresultsignature)
