---
title: DigitalSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 130
---

## DigitalSignature class

Contains Digital signature properties.



**Inheritance:** [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The DigitalSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#) | Initialize Digital signature with default parameters. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#System.String) | Initialize Digital signature with known SignatureId. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#System.Security.Cryptography.X509Certificates.X509Certificate2) | Create Digital signature with specified certificate. |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/digitalsignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/digitalsignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/digitalsignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/digitalsignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/digitalsignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/digitalsignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/digitalsignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/digitalsignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/digitalsignature/height) | Specifies height of signature. |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate) | Gets or sets the X509 certificate. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments) | Gets or sets the signing purpose comment. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid) | Keeps true if this digital signature is valid and the document has not been tampered with. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time) | Gets or sets the time the document was signed. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name) | Specifies the custom store name of the certificate. |
| [x_ad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/x_ad_es_type) | XAdES type [`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature#x_ad_es_type). Default value is None (XAdES is off).<br/>At this moment XAdES signature type is supported only for Spreadsheet documents. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint) | Gets the thumbprint of a certificate. |


### Methods
| Method | Description |
| :- | :- |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#) | Load Digital signatures from all system X509 Certificates Stores. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#System.String) | Load Digital signatures from a certificate storage. |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/#) | Clone Barcode Signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature)
