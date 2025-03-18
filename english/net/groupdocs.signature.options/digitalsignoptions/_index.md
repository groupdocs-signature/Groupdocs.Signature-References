---
title: DigitalSignOptions
second_title: GroupDocs.Signature for .NET API Reference
description: Represents the Digital signature options.
type: docs
weight: 1550
url: /net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Represents the Digital signature options.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Initializes a new instance of the DigitalSignOptions class with default values. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Initializes a new instance of the DigitalSignOptions class with certificate stream. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Initializes a new instance of the DigitalSignOptions class with certificate file. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Initializes a new instance of the DigitalSignOptions class with certificate stream and image stream. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Initializes a new instance of the DigitalSignOptions class with certificate stream and image file. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Initializes a new instance of the DigitalSignOptions class with certificate file and image stream. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Initializes a new instance of the DigitalSignOptions class with certificate file and image file. |

## Properties

| Name | Description |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Put signature on all document pages. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Additional signature appearance. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Specify border settings |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Gets or sets the digital certificate file path. This property is used only if CertificateStream is not specified. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Gets or sets digital certificate stream. If this property is specified it is always used instead CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Gets or sets the signature contact. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Gets or sets a custom hash signing function, allowing users to implement their own digital signing logic. This enables signing with external certificates and supports different hash algorithms. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Get or set the Document Type of the Signature Options [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signature Extensions. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Gets or sets the hash algorithm to be used for cryptographic operations. Supported exclusively for digital signatures in PDF files. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horizontal alignment of signature on document page. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Gets or sets the signature image file path. This property is used only if ImageStream is not specified. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Gets or sets the signature image stream. If this property is specified it is always used instead ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (works if horizontal alignment is not specified). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Gets or sets the signature location. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Gets or sets the space between Sign and Document edges. (works ONLY if horizontal or vertical alignment are specified). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Gets or sets document page number for signing. Minimal and default value is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options to specify pages to be signed. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Gets or sets the password of digital certificate. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Gets or sets the reason of signature. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectangle of area to put the image on document. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotation angle of signature on document page (clockwise). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Defines where shape should be presented in the document layout. Avaliable only for Word documents |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Gets or sets properties of document digital signature. For signing Pdf documents it is possible to set advanced properties by using instance of [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Get the Signature Type [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Stretch mode on Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (works if vertical alignment is not specified). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Gets/sets ltv(Long Term Validation) validation flag. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertical alignment of signature on document page. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Gets or sets the visibility of signature. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Width of Signature on Document Page in Measure values (pixels, percents or millimeters [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES type [`XAdESType`](./xadestype). Default value is None (XAdES is off). At this moment XAdES signature type is supported only for Spreadsheet documents. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Gets or sets the Z-order position of text signature. Determines the display order of overlapping signatures. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Clears internal resources |

### Remarks

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### See Also

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
