---
title: QrCodeSignOptions
second_title: GroupDocs.Signature for .NET API Reference
description: Represents the QRCode signature options.
type: docs
weight: 1540
url: /net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Represents the QR-Code signature options.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Initializes a new instance of the QRCodeSignOptions class with default values. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Initializes a new instance of the QRCodeSignOptions class with text. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Initializes a new instance of the BarcodeSignOptions class with text. |

## Properties

| Name | Description |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Put signature on all document pages. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Additional signature appearance. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Gets or sets the signature background settings. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Specify border settings |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Gets or sets the alignment of text in the result QR-code image. Default value is None. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Gets or sets custom object to serialize to QR-Code content. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Gets or sets implementation of [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Get or set the Document Type of the Signature Options [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Gets or sets QR-Code type. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signature Extensions. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Gets or sets the font of signature. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Gets or sets the Fore color of QR-Code bars Using of this property could cause problems with verification. Use it carefully. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Gets or sets the title of text form field to put text signature into it. This property could be used only with SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Gets or sets the type of form field to put text signature into it. This property could be used only with SignatureImplementation = TextToFormField. Value by default is AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType property). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horizontal alignment of signature on document page. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Gets or sets the space between QR-Code elements and result image borders. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType property). (works if horizontal alignment is not specified). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Gets or sets the QR-code logo image file name. This property in use only if LogoStream is not specified. Using of this property could cause problems with verification. Use it carefully. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Gets or sets the QR-code logo image stream. If this property is specified it is always used instead LogoFilePath. Using of this property could cause problems with verification. Use it carefully. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Gets or sets the space between Sign and Document edges. (works ONLY if horizontal or vertical alignment are specified). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Gets or sets the native attribute. If it is set document specific signatures could be used. Native text watermark for WordProcessing documents is different than regular, for example. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Gets or sets document page number for signing. Minimal and default value is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options to specify pages to be signed. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Gets or sets flag to get QR-Code image content of a signature which was put on document page. If this flag is set true, QR-Code signature image content will keep raw image data by required format [`ReturnContentType`](./returncontenttype). By default this option is disabled. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. By default it set to Null. That means to return QR-Code image content in original format. This image format is specified at [`Format`](../../groupdocs.signature.domain/qrcodesignature/format) Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than QR-Code image content in .png format will be returned. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Rotation angle of signature on document page (clockwise). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Gets or sets the type of shape to put text. This property could be used only with SignatureImplementation = TextStamp. Value by default is Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Gets or sets the unique ID of signature. It can be used in signature verification options. Property is supported for Pdf documents only. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Gets or sets the type of text signature implementation. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Get the Signature Type [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Stretch mode on Document Page. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Gets or sets the text of signature. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Horizontal alignment of text inside a signature. This feature is supported only for Image and Annotation signature implementations (see [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation property). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Vertical alignment of text inside a signature. This feature is supported only for Image signature implementation (see [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation property). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType property). (works if vertical alignment is not specified). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Vertical alignment of signature on document page. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Width of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType property). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Gets or sets the Z-order position of text signature. Determines the display order of overlapping signatures. |

### Remarks

**Learn more**

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### See Also

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
