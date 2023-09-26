---
title: ImageSignOptions
second_title: GroupDocs.Signature for .NET API Reference
description: Represents the Image signature options.
type: docs
weight: 1520
url: /net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Represents the Image signature options.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Initializes a new instance of the ImageSignOptions class with default values. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Initializes a new instance of the ImageSignOptions class with image stream. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Initializes a new instance of the ImageSignOptions class with image file. |

## Properties

| Name | Description |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Put signature on all document pages. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Additional signature appearance. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Specify border settings |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Get or set the Document Type of the Signature Options [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Signature Extensions. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Height of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Horizontal alignment of signature on document page. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Gets or sets the signature image file path. This property is used only if ImageStream is not specified. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Gets or sets the signature image stream. If this property is specified it is always used instead ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Left X position of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (works if horizontal alignment is not specified). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Gets or sets the space between Sign and Document edges. (works ONLY if horizontal or vertical alignment are specified). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Gets or sets document page number for signing. Minimal and default value is 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Options to specify pages to be signed. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Rectangle of area to put the image on document. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Rotation angle of signature on document page (clockwise). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Get the Signature Type [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Stretch mode on Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Top Y Position of Signature on Document Page in Measure values (pixels, percents or millimeters see [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (works if vertical alignment is not specified). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Vertical alignment of signature on document page. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Width of Signature on Document Page in Measure values (pixels, percents or millimeters [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Gets or sets the Z-order position of text signature. Determines the display order of overlapping signatures. |

## Methods

| Name | Description |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Creates a new instance of the ImageSignOptions class with predefined Image from Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Clears internal resources |

### Remarks

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### See Also

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
