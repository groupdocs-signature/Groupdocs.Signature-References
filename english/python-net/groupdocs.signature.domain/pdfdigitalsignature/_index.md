---
title: PdfDigitalSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 310
---

## PdfDigitalSignature class

Contains Pdf Digital signature properties.



**Inheritance:** [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature) → 
[`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The PdfDigitalSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#) | Initialize Pdf Digital Signature with no certificate. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#System.Security.Cryptography.X509Certificates.X509Certificate2) | Create Pdf Digital signature with specified certificate. |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/height) | Specifies height of signature. |
| [certificate](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/certificate) | Gets or sets the X509 certificate. |
| [comments](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/comments) | Gets or sets the signing purpose comment. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/is_valid) | Keeps true if this digital signature is valid and the document has not been tampered with. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/sign_time) | Gets or sets the time the document was signed. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/certificate_custom_store_name) | Specifies the custom store name of the certificate. |
| [x_ad_es_type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/x_ad_es_type) | XAdES type [`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature#x_ad_es_type). Default value is None (XAdES is off).<br/>At this moment XAdES signature type is supported only for Spreadsheet documents. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/thumbprint) | Gets the thumbprint of a certificate. |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info) | Information provided by the signer to enable a recipient to contact the signer<br/>to verify the signature, e.g. a phone number. |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location) | The CPU host name or physical location of the signing. |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason) | The reason for the signing, such as (I agreeРІР‚В¦). |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type) | Type of Pdf digital signature. |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp) | Time stamp for Pdf digital signature.<br/>Default value is null. |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties) | Force to show/hide signature properties. In case ShowProperties is true signature<br/>field has predefined format of appearance <br/>Digitally signed by {[`PdfDigitalSignature.contact_info`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature#contact_info)} Date: {Date} Reason: {[`PdfDigitalSignature.reason`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature#reason)}<br/>Location: {[`PdfDigitalSignature.location`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature#location)}<br/>ShowProperties is true by default. |


### Methods
| Method | Description |
| :- | :- |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/load_digital_signatures/#) | Load Digital signatures from all system X509 Certificates Stores. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/load_digital_signatures/#str) | Load Digital signatures from a certificate storage. |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/#) | Clone Barcode Signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature)
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature)
