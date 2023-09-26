---
title: FormFieldSignOptions
second_title: GroupDocs.Signature for .NET API Reference
description: Represents class of the FormField signature options for Pdf documents.
type: docs
weight: 1480
url: /net/groupdocs.signature.options/formfieldsignoptions/
---
## FormFieldSignOptions class

Represents class of the FormField signature options for Pdf documents.

```csharp
public sealed class FormFieldSignOptions : TextSignOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [FormFieldSignOptions](formfieldsignoptions#constructor)() | Initializes a new instance of the PdfFormFieldSignOptions class with default values. |
| [FormFieldSignOptions](formfieldsignoptions#constructor_1)(FormFieldSignature) | Initializes a new instance of the PdfFormFieldSignOptions class with FormField signature. |

## Properties

| Name | Description |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Put signature on all document pages. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Additional signature appearance. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Gets or sets the signature background settings. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Specify border settings |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Get or set the Document Type of the Signature Options [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signature Extensions. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Gets or sets the font of signature. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | Gets or sets the fore color of signature. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Gets or sets the title of text form field to put text signature into it. This property could be used only with SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Gets or sets the type of form field to put text signature into it. This property could be used only with SignatureImplementation = TextToFormField. Value by default is AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType property). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Horizontal alignment of signature on document page. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType property). (works if horizontal alignment is not specified). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Gets or sets the space between Sign and Document edges. (works ONLY if horizontal or vertical alignment are specified). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Gets or sets the native attribute. If it is set document specific signatures could be used. Native text watermark for WordProcessing documents is different than regular, for example. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Gets or sets document page number for signing. Minimal and default value is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options to specify pages to be signed. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Rotation angle of signature on document page (clockwise). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Gets or sets the type of shape to put text. This property could be used only with SignatureImplementation = TextStamp. Value by default is Rectangle. |
| [Signature](../../groupdocs.signature.options/formfieldsignoptions/signature) { get; set; } | Gets or sets the FormField of signature. |
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

* Basic usage of creating FormField electronic signature by GroupDocs.Signature: [How to eSign document with FormField signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature)
* Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with FormField signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced)

### See Also

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
