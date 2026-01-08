---
title: ImageSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 210
---

## ImageSignOptions class

Represents the Image signature options.



**Inheritance:** [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions) → 
[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)



The ImageSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#) | Initializes a new instance of the ImageSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#System.String) | Initializes a new instance of the ImageSignOptions class with image file. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#io.RawIOBase) | Initializes a new instance of the ImageSignOptions class with image stream. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/imagesignoptions/page_number) | Gets or sets document page number for signing.<br/>Minimal and default value is 1. |
| [all_pages](/signature/python-net/groupdocs.signature.options/imagesignoptions/all_pages) | Put signature on all document pages. |
| [appearance](/signature/python-net/groupdocs.signature.options/imagesignoptions/appearance) | Additional signature appearance. |
| [extensions](/signature/python-net/groupdocs.signature.options/imagesignoptions/extensions) | Signature Extensions. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/imagesignoptions/pages_setup) | Options to specify pages to be signed. |
| [signature_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/signature_type) | Get the Signature Type [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) |
| [document_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/document_type) | Get or set the Document Type of the Signature Options [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype) |
| [z_order](/signature/python-net/groupdocs.signature.options/imagesignoptions/z_order) | Gets or sets the Z-order position of text signature.        <br/>Determines the display order of overlapping signatures. |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/imagesignoptions/hash_algorithm) | Gets or sets the hash algorithm to be used for cryptographic operations.<br/>Supported exclusively for digital signatures in PDF files. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path) | Gets or sets the signature image file path.<br/>This property is used only if ImageStream is not specified. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream) | Gets or sets the signature image stream.<br/>If this property is specified it is always used instead ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left) | Left X position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType).<br/>(works if horizontal alignment is not specified). |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top) | Top Y Position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType).<br/>(works if vertical alignment is not specified). |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width) | Width of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height) | Height of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type) | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type) | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch) | Stretch mode on Document Page. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle) | Rotation angle of signature on document page (clockwise). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment) | Horizontal alignment of signature on document page. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment) | Vertical alignment of signature on document page. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin) | Gets or sets the space between Sign and Document edges.<br/>(works ONLY if horizontal or vertical alignment are specified). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type) | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency) | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position) | Defines where shape should be presented in the document layout. Avaliable only for Word documents |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle) | Rectangle of area to put the image on document. |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border) | Specify border settings |


### Methods
| Method | Description |
| :- | :- |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#System.String) | Creates a new instance of the ImageSignOptions class with predefined Image from Base64. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype)
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions)
* class [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype)
* class [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)
* class [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype)
