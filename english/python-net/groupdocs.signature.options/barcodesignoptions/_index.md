---
title: BarcodeSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---

## BarcodeSignOptions class

Represents the Barcode signature options.



**Inheritance:** [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions) → 
[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions) → 
[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)



The BarcodeSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#) | Initializes a new instance of the BarcodeSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#System.String) | Initializes a new instance of the BarcodeSignOptions class with text. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#System.String-groupdocs.signature.domain.BarcodeType) | Initializes a new instance of the BarcodeSignOptions class with text. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/barcodesignoptions/page_number) | Gets or sets document page number for signing.<br/>Minimal and default value is 1. |
| [all_pages](/signature/python-net/groupdocs.signature.options/barcodesignoptions/all_pages) | Put signature on all document pages. |
| [appearance](/signature/python-net/groupdocs.signature.options/barcodesignoptions/appearance) | Additional signature appearance. |
| [extensions](/signature/python-net/groupdocs.signature.options/barcodesignoptions/extensions) | Signature Extensions. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/barcodesignoptions/pages_setup) | Options to specify pages to be signed. |
| [signature_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/signature_type) | Get the Signature Type [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) |
| [document_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/document_type) | Get or set the Document Type of the Signature Options [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype) |
| [z_order](/signature/python-net/groupdocs.signature.options/barcodesignoptions/z_order) | Gets or sets the Z-order position of text signature.        <br/>Determines the display order of overlapping signatures. |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/barcodesignoptions/hash_algorithm) | Gets or sets the hash algorithm to be used for cryptographic operations.<br/>Supported exclusively for digital signatures in PDF files. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left) | Left X position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType property).<br/>(works if horizontal alignment is not specified). |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top) | Top Y Position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType property).<br/>(works if vertical alignment is not specified). |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width) | Width of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType property). |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height) | Height of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType property). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type) | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type) | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch) | Stretch mode on Document Page. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle) | Rotation angle of signature on document page (clockwise). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment) | Horizontal alignment of signature on document page. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment) | Vertical alignment of signature on document page. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin) | Gets or sets the space between Sign and Document edges.<br/>(works ONLY if horizontal or vertical alignment are specified). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type) | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency) | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque). |
| [text](/signature/python-net/groupdocs.signature.options/barcodesignoptions/text) | Gets or sets the text of signature. |
| [font](/signature/python-net/groupdocs.signature.options/barcodesignoptions/font) | Gets or sets the font of signature. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color) | Gets or sets the Fore color of Barcode bars<br/>Using of this property could cause problems with verification. Use it carefully. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/barcodesignoptions/signature_implementation) | Gets or sets the type of text signature implementation. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/text_horizontal_alignment) | Horizontal alignment of text inside a signature.<br/>This feature is supported only for Image and Annotation signature implementations <br/>(see [`TextSignatureImplementation`](/signature/python-net/groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation property). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/text_vertical_alignment) | Vertical alignment of text inside a signature.<br/>This feature is supported only for Image signature implementation <br/>(see [`TextSignatureImplementation`](/signature/python-net/groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation property). |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/barcodesignoptions/form_text_field_title) | Gets or sets the title of text form field to put text signature into it.<br/>This property could be used only with SignatureImplementation = TextToFormField. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/form_text_field_type) | Gets or sets the type of form field to put text signature into it.<br/>This property could be used only with SignatureImplementation = TextToFormField.<br/>Value by default is AllTextTypes. |
| [shape_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/shape_type) | Gets or sets the type of shape to put text.<br/>This property could be used only with SignatureImplementation = TextStamp.<br/>Value by default is Rectangle. |
| [signature_id](/signature/python-net/groupdocs.signature.options/barcodesignoptions/signature_id) | Gets or sets the unique ID of signature. It can be used in signature verification options. <br/>Property is supported for Pdf documents only. |
| [border](/signature/python-net/groupdocs.signature.options/barcodesignoptions/border) | Specify border settings |
| [background](/signature/python-net/groupdocs.signature.options/barcodesignoptions/background) | Gets or sets the signature background settings. |
| [native](/signature/python-net/groupdocs.signature.options/barcodesignoptions/native) | Gets or sets the native attribute. If it is set document specific signatures could be used.<br/>Native text watermark for WordProcessing documents is different than regular, for example. |
| [shape_position](/signature/python-net/groupdocs.signature.options/barcodesignoptions/shape_position) | Defines where shape should be presented in the document layout. Avaliable only for Word documents |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) | Gets or sets Barcode type. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins) | Gets or sets the space between Barcode elements and result image borders. |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment) | Gets or sets the alignment of text in the result Barcode image.<br/>Default value is None. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content) | Gets or sets flag to get Barcode image content of a signature which was put on document page.<br/>If this flag is set true, Barcode signature image content will keep raw image data by required format [`BarcodeSignOptions.return_content_type`](/signature/python-net/groupdocs.signature.options/barcodesignoptions#return_content_type).<br/>By default this option is disabled. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type) | Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled.<br/>By default it set to Null. That means to return Barcode image content in original format. <br/>This image format is specified at [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature#format)<br/>Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. <br/>If provided format is not supported than Barcode image content in .png format will be returned. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions)
* class [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype)
* class [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype)
* class [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)
* class [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype)
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions)
* class [`TextSignatureImplementation`](/signature/python-net/groupdocs.signature.domain/textsignatureimplementation)
