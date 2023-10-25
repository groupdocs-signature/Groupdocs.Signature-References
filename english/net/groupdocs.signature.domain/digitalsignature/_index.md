---
title: DigitalSignature
second_title: GroupDocs.Signature for .NET API Reference
description: Contains Digital signature properties.
type: docs
weight: 150
url: /net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

Contains Digital signature properties.

```csharp
public class DigitalSignature : BaseSignature
```

## Constructors

| Name | Description |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | Initialize Digital signature with default parameters. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | Initialize Digital signature with known SignatureId. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | Create Digital signature with specified certificate. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | Create Digital signature based on specified X509 store. First certificate from specified store will be used. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | Create Digital signature based on specified X509 Store and index of certificate. |

## Properties

| Name | Description |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | Gets or sets the X509 certificate. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | Specifies the custom store name of the certificate. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | Specifies the store location of the certificate |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | Specifies the store name of the certificate. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | Gets or sets the signing purpose comment. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | Get or set the signature creation date. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | Get the flag that indicates if this signature was deleted from the document. This property is being used only for document history log records to keep the list of deleted signatures. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | Specifies height of signature. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | Get or set flag to indicate if this component is Signature or document content. This property is being used with Update method to set element as signature (true) or document element (false). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | Keeps true if this digital signature is valid and the document has not been tampered with. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | Specifies left position of signature. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | Get or set the signature modification date. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | Specifies the page signature was found on. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Unique signature identifier to modify signature in the document over Update or Delete methods. This property will be set automatically after Sign or Search method being called. If this property was saved before it can be set manually to manipulate the signature. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | Specifies the type of signature. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | Gets or sets the time the document was signed. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | Gets the thumbprint of a certificate. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | Specifies top position of signature. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | Specifies width of signature. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES type [`XAdESType`](./xadestype). Default value is None (XAdES is off). At this moment XAdES signature type is supported only for Spreadsheet documents. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Clone Barcode Signature instance. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | Overwrites Equals method to compare signature properties |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | Overrides GetHashCode method |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | Load Digital signatures from all system X509 Certificates Stores. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | Load Digital signatures from a certificate storage. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | Load Digital signatures from a certificate storage. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | Load Digital signatures from a digital certificate storage placed in specific location. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | Load Digital signatures from a digital certificate storage placed in specific location. |

### See Also

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
