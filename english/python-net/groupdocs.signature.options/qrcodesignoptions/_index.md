---
title: QrCodeSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 360
---

## QrCodeSignOptions class

Represents the QR-Code signature options.



**Inheritance:** [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions) → 
[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions) → 
[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)



The QrCodeSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#) | Initializes a new instance of the QRCodeSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#System.String) | Initializes a new instance of the QRCodeSignOptions class with text. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#System.String-groupdocs.signature.domain.QrCodeType) | Initializes a new instance of the BarcodeSignOptions class with text. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/page_number) | Gets or sets document page number for signing.<br/>Minimal and default value is 1. |
| [all_pages](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/all_pages) | Put signature on all document pages. |
| [appearance](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/appearance) | Additional signature appearance. |
| [extensions](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/extensions) | Signature Extensions. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/pages_setup) | Options to specify pages to be signed. |
| [signature_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/signature_type) | Get the Signature Type [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) |
| [document_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/document_type) | Get or set the Document Type of the Signature Options [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype) |
| [z_order](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/z_order) | Gets or sets the Z-order position of text signature.        <br/>Determines the display order of overlapping signatures. |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/hash_algorithm) | Gets or sets the hash algorithm to be used for cryptographic operations.<br/>Supported exclusively for digital signatures in PDF files. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left) | Left X position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType property).<br/>(works if horizontal alignment is not specified). |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top) | Top Y Position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType property).<br/>(works if vertical alignment is not specified). |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width) | Width of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType property). |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height) | Height of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType property). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type) | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type) | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch) | Stretch mode on Document Page. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle) | Rotation angle of signature on document page (clockwise). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment) | Horizontal alignment of signature on document page. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment) | Vertical alignment of signature on document page. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin) | Gets or sets the space between Sign and Document edges.<br/>(works ONLY if horizontal or vertical alignment are specified). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type) | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency) | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque). |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/text) | Gets or sets the text of signature. |
| [font](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/font) | Gets or sets the font of signature. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color) | Gets or sets the Fore color of QR-Code bars<br/>Using of this property could cause problems with verification. Use it carefully. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/signature_implementation) | Gets or sets the type of text signature implementation. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/text_horizontal_alignment) | Horizontal alignment of text inside a signature.<br/>This feature is supported only for Image and Annotation signature implementations <br/>(see [`TextSignatureImplementation`](/signature/python-net/groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation property). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/text_vertical_alignment) | Vertical alignment of text inside a signature.<br/>This feature is supported only for Image signature implementation <br/>(see [`TextSignatureImplementation`](/signature/python-net/groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation property). |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/form_text_field_title) | Gets or sets the title of text form field to put text signature into it.<br/>This property could be used only with SignatureImplementation = TextToFormField. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/form_text_field_type) | Gets or sets the type of form field to put text signature into it.<br/>This property could be used only with SignatureImplementation = TextToFormField.<br/>Value by default is AllTextTypes. |
| [shape_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/shape_type) | Gets or sets the type of shape to put text.<br/>This property could be used only with SignatureImplementation = TextStamp.<br/>Value by default is Rectangle. |
| [signature_id](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/signature_id) | Gets or sets the unique ID of signature. It can be used in signature verification options. <br/>Property is supported for Pdf documents only. |
| [border](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/border) | Specify border settings |
| [background](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/background) | Gets or sets the signature background settings. |
| [native](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/native) | Gets or sets the native attribute. If it is set document specific signatures could be used.<br/>Native text watermark for WordProcessing documents is different than regular, for example. |
| [shape_position](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/shape_position) | Defines where shape should be presented in the document layout. Avaliable only for Word documents |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) | Gets or sets QR-Code type. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins) | Gets or sets the space between QR-Code elements and result image borders. |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment) | Gets or sets the alignment of text in the result QR-code image.<br/>Default value is None. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path) | Gets or sets the QR-code logo image file name.<br/>This property in use only if LogoStream is not specified.<br/>Using of this property could cause problems with verification. Use it carefully. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream) | Gets or sets the QR-code logo image stream.<br/>If this property is specified it is always used instead LogoFilePath.<br/>Using of this property could cause problems with verification. Use it carefully. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data) | Gets or sets custom object to serialize to QR-Code content. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption) | Gets or sets implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content) | Gets or sets flag to get QR-Code image content of a signature which was put on document page.<br/>If this flag is set true, QR-Code signature image content will keep raw image data by required format [`QrCodeSignOptions.return_content_type`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions#return_content_type).<br/>By default this option is disabled. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type) | Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled.<br/>By default it set to Null. That means to return QR-Code image content in original format. <br/>This image format is specified at [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature#format)<br/>Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. <br/>If provided format is not supported than QR-Code image content in .png format will be returned. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
* class [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype)
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions)
* class [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)
* class [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype)
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions)
* class [`TextSignatureImplementation`](/signature/python-net/groupdocs.signature.domain/textsignatureimplementation)
