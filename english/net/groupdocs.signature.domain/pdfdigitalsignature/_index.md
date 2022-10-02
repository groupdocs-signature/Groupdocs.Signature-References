---
title: PdfDigitalSignature
second_title: GroupDocs.Signature for .NET API Reference
description: Contains Pdf Digital signature properties.
type: docs
weight: 630
url: /net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Contains Pdf Digital signature properties.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | Initialize Pdf Digital Signature with no certificate. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | Create Pdf Digital signature with specified certificate. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | Initialize Pdf Digital Signature based on specified X509 store. First certificate from specified store will be used. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | Create Pdf Digital signature based on specified X509 Store and index of certificate. |

## Properties

| Name | Description |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Gets or sets the X509 certificate. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specifies the store location of the certificate |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specifies the store name of the certificate. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Gets or sets the signing purpose comment. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Get or set the signature creation date. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Get the flag that indicates if this signature was deleted from the document. This property is being used only for document history log records to keep the list of deleted signatures. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifies height of signature. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Get or set flag to indicate if this component is Signature or document content. This property is being used with Update method to set element as signature (true) or document element (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Keeps true if this digital signature is valid and the document has not been tampered with. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifies left position of signature. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | The CPU host name or physical location of the signing. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Get or set the signature modification date. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifies the page signature was found on. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | The reason for the signing, such as (I agreeРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance Digitally signed by {[`ContactInfo`](./contactinfo)} Date: {Date} Reason: {[`Reason`](./reason)} Location: {[`Location`](./location)} ShowProperties is true by default. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unique signature identifier to modify signature in the document over Update or Delete methods. This property will be set automatically after Sign or Search method being called. If this property was saved before it can be set manually to manipulate the signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifies the type of signature. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Gets or sets the time the document was signed. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Gets the thumbprint of a certificate. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Time stamp for Pdf digital signature. Default value is null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifies top position of signature. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Type of Pdf digital signature. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifies width of signature. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES type [`XAdESType`](../digitalsignature/xadestype). Default value is None (XAdES is off). At this moment XAdES signature type is supported only for Spreadsheet documents. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Clone Barcode Signature instance. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | Overwrites Equals method to compare signature properties |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | Overrides GetHashCode method |

### See Also

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
