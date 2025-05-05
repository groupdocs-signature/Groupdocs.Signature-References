---
title: DigitalSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 100
---

## DigitalSignOptions class

Represents the Digital signature options.



**Inheritance:** [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions) → 
[`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions) → 
[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)



The DigitalSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#) | Initializes a new instance of the DigitalSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#str) | Initializes a new instance of the DigitalSignOptions class with certificate file. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#io.RawIOBase) | Initializes a new instance of the DigitalSignOptions class with certificate stream. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#str-str) | Initializes a new instance of the DigitalSignOptions class with certificate file and image file. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#str-io.RawIOBase) | Initializes a new instance of the DigitalSignOptions class with certificate file and image stream. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#io.RawIOBase-str) | Initializes a new instance of the DigitalSignOptions class with certificate stream and image file. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#io.RawIOBase-io.RawIOBase) | Initializes a new instance of the DigitalSignOptions class with certificate stream and image stream. |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/digitalsignoptions/page_number) | Gets or sets document page number for signing.<br/>Minimal and default value is 1. |
| [all_pages](/signature/python-net/groupdocs.signature.options/digitalsignoptions/all_pages) | Put signature on all document pages. |
| [appearance](/signature/python-net/groupdocs.signature.options/digitalsignoptions/appearance) | Additional signature appearance. |
| [extensions](/signature/python-net/groupdocs.signature.options/digitalsignoptions/extensions) | Signature Extensions. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/digitalsignoptions/pages_setup) | Options to specify pages to be signed. |
| [signature_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature_type) | Get the Signature Type [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) |
| [document_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/document_type) | Get or set the Document Type of the Signature Options [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype) |
| [z_order](/signature/python-net/groupdocs.signature.options/digitalsignoptions/z_order) | Gets or sets the Z-order position of text signature.        <br/>Determines the display order of overlapping signatures. |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/digitalsignoptions/hash_algorithm) | Gets or sets the hash algorithm to be used for cryptographic operations.<br/>Supported exclusively for digital signatures in PDF files. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/image_file_path) | Gets or sets the signature image file path.<br/>This property is used only if ImageStream is not specified. |
| [image_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/image_stream) | Gets or sets the signature image stream.<br/>If this property is specified it is always used instead ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left) | Left X position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType).<br/>(works if horizontal alignment is not specified). |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top) | Top Y Position of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) LocationMeasureType).<br/>(works if vertical alignment is not specified). |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width) | Width of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height) | Height of Signature on Document Page in Measure values <br/>(pixels, percents or millimeters see [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type) | Measure type (pixels, percents or millimeters) for Left and Top properties. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type) | Measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch) | Stretch mode on Document Page. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle) | Rotation angle of signature on document page (clockwise). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment) | Horizontal alignment of signature on document page. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment) | Vertical alignment of signature on document page. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin) | Gets or sets the space between Sign and Document edges.<br/>(works ONLY if horizontal or vertical alignment are specified). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type) | Gets or sets the measure type (pixels, percents or millimeters) for Margin. |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency) | Gets or sets the signature transparency (value from 0.0 (opaque) through 1.0 (clear)). Default value is 0 (opaque). |
| [shape_position](/signature/python-net/groupdocs.signature.options/digitalsignoptions/shape_position) | Defines where shape should be presented in the document layout. Avaliable only for Word documents |
| [rectangle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rectangle) | Rectangle of area to put the image on document. |
| [border](/signature/python-net/groupdocs.signature.options/digitalsignoptions/border) | Specify border settings |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason) | Gets or sets the reason of signature. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact) | Gets or sets the signature contact. |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location) | Gets or sets the signature location. |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password) | Gets or sets the password of digital certificate. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature) | Gets or sets properties of document digital signature. <br/>For signing Pdf documents it is possible to set advanced properties by using instance of [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature) |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path) | Gets or sets the digital certificate file path.<br/>This property is used only if CertificateStream is not specified. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream) | Gets or sets digital certificate stream.<br/>If this property is specified it is always used instead CertificateFilePath. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible) | Gets or sets the visibility of signature. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv) | Gets/sets ltv(Long Term Validation) validation flag. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash) | Gets or sets a custom hash signing function, allowing users to implement their own digital signing logic.<br/>This enables signing with external certificates and supports different hash algorithms. |
| [x_ad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/x_ad_es_type) | XAdES type [`DigitalSignOptions.x_ad_es_type`](/signature/python-net/groupdocs.signature.options/digitalsignoptions#x_ad_es_type). Default value is None (XAdES is off).<br/>At this moment XAdES signature type is supported only for Spreadsheet documents. |


### Methods
| Method | Description |
| :- | :- |
| [from_base64](/signature/python-net/groupdocs.signature.options/digitalsignoptions/from_base64/#str) | Creates a new instance of the ImageSignOptions class with predefined Image from Base64. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions)
* class [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype)
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions)
* class [`MeasureType`](/signature/python-net/groupdocs.signature.domain/measuretype)
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature)
* class [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)
* class [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype)
