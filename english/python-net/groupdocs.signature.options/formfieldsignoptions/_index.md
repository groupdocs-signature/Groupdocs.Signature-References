---
title: FormFieldSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 140
---

## FormFieldSignOptions class

Represents class of the FormField signature options for Pdf documents.



**Inheritance:** [`FormFieldSignOptions`](/signature/python-net/groupdocs.signature.options/formfieldsignoptions) → 
[`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions) → 
[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)



The FormFieldSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#) | Initializes a new instance of the PdfFormFieldSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#groupdocs.signature.domain.FormFieldSignature) | Initializes a new instance of the PdfFormFieldSignOptions class with FormField signature. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/page_number) | Gets or sets document page number for signing.<br/>Minimal and default value is 1. |
| [all_pages](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/all_pages) | Put signature on all document pages. |
| [appearance](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/appearance) | Additional signature appearance. |
| [extensions](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/extensions) | Signature Extensions. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/pages_setup) | Options to specify pages to be signed. |
| [signature_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature_type) | Get the Signature Type [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) |
| [document_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/document_type) | Get or set the Document Type of the Signature Options [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype) |
| [z_order](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/z_order) | Gets or sets the Z-order position of text signature.        <br/>Determines the display order of overlapping signatures. |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/hash_algorithm) | Gets or sets the hash algorithm to be used for cryptographic operations.<br/>Supported exclusively for digital signatures in PDF files. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left) | Left X position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType property).<br/>(works if horizontal alignment is not specified). |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top) | Top Y Position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType property).<br/>(works if vertical alignment is not specified). |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width) | Width of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType property). |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height) | Height of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType property). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type) | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type) | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch) | Stretch mode on Document Page. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle) | Rotation angle of signature on document page (clockwise). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment) | Horizontal alignment of signature on document page. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment) | Vertical alignment of signature on document page. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin) | Gets or sets the space between Sign and Document edges.<br/>(works ONLY if horizontal or vertical alignment are specified). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type) | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency) | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque). |
| [text](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/text) | Gets or sets the text of signature. |
| [font](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/font) | Gets or sets the font of signature. |
| [fore_color](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/fore_color) | Gets or sets the fore color of signature. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature_implementation) | Gets or sets the type of text signature implementation. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/text_horizontal_alignment) | Horizontal alignment of text inside a signature.<br/>This feature is supported only for Image and Annotation signature implementations <br/>(see [`TextSignatureImplementation`](/signature/python-net/groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation property). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/text_vertical_alignment) | Vertical alignment of text inside a signature.<br/>This feature is supported only for Image signature implementation <br/>(see [`TextSignatureImplementation`](/signature/python-net/groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation property). |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/form_text_field_title) | Gets or sets the title of text form field to put text signature into it.<br/>This property could be used only with SignatureImplementation = TextToFormField. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/form_text_field_type) | Gets or sets the type of form field to put text signature into it.<br/>This property could be used only with SignatureImplementation = TextToFormField.<br/>Value by default is AllTextTypes. |
| [shape_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/shape_type) | Gets or sets the type of shape to put text.<br/>This property could be used only with SignatureImplementation = TextStamp.<br/>Value by default is Rectangle. |
| [signature_id](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature_id) | Gets or sets the unique ID of signature. It can be used in signature verification options. <br/>Property is supported for Pdf documents only. |
| [border](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/border) | Specify border settings |
| [background](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/background) | Gets or sets the signature background settings. |
| [native](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/native) | Gets or sets the native attribute. If it is set document specific signatures could be used.<br/>Native text watermark for WordProcessing documents is different than regular, for example. |
| [shape_position](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/shape_position) | Defines where shape should be presented in the document layout. Avaliable only for Word documents |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature) | Gets or sets the FormField of signature. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype)
* class [`FormFieldSignOptions`](/signature/python-net/groupdocs.signature.options/formfieldsignoptions)
* class [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype)
* class [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)
* class [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype)
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions)
* class [`TextSignatureImplementation`](/signature/python-net/groupdocs.signature.domain/textsignatureimplementation)
