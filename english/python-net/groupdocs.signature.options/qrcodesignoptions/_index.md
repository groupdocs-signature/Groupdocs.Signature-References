---
title: QrCodeSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents the QR-Code signature options."
type: docs
url: /python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

Represents the QR-Code signature options.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

The QrCodeSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Initializes a new instance of the QRCodeSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Initializes a QR code signature options instance with the specified text. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Initializes a new instance of the QrCodeSignOptions class with text. |

### Properties
| Property | Description |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | The alignment of text in the resulting QR-code image, default value is None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | The custom object to serialize to QR-Code content. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | The data encryption implementation used to encode and decode QR code signature text or data. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | The QR-Code type. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | The foreground color of QR code bars; using this property could cause verification problems, so use it carefully. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | The height of the signature area on the document page in measure units (pixels, percents, or millimeters; see `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | The horizontal alignment of the QR code on a document page. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | The space between QR code elements and result image borders. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | The left X position of the signature area on a document page in measure units (pixels, percents, or millimeters). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | The measure type (pixels, percents or millimeters) for left and top properties. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | The QR-code logo image file name. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | The QR-code logo image stream. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | The space that is specified by default between Image and Document edges (works if horizontal or vertical alignment is specified). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | The margin measurement type (pixels, percents or millimeters). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | The flag to retrieve QR-Code image content of a signature placed on a document page. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | The file type of the returned image content of the QR‑Code signature when the `return_content` property is enabled. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | The rotation angle in degrees, clockwise. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | The measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | The stretch mode on the document page. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | The top Y position of the signature area on a document page in measure units (pixels, percents, or millimeters). The unit is defined by the `LocationMeasureType` property of type `MeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | The transparency of the QR code signature. The value ranges from 0.0 to 1.0, with a default of 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | The vertical alignment of the image on a document page. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | The width of the signature area on the document page in measure values (pixels, percent, or millimeters as defined by `MeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | The signature will be placed on all document pages. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | The additional signature appearance. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | The signature background settings. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | The border settings. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | The document type of the signature options (`DocumentType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | The signature extensions. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | The font of the signature. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | The title of the text form field to place the text signature into. Can be used only when `signature_implementation` is set to `TextSignatureImplementation.FORM_FIELD`. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | The type of form field to place the text signature into. This property is applicable only when `signature_implementation` is set to `TextSignatureImplementation.FORM_FIELD` (i.e., TextToFormField). The default value is `FormTextFieldType.ALL_TEXT_TYPES`. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | The hash algorithm to be used for cryptographic operations. Supported exclusively for digital signatures in PDF files. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | The native attribute. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | The document page number for signing. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | The options to specify pages to be signed. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | The shape position defines where the shape should be presented in the document layout. Available only for Word documents. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | The type of shape to put text. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | The unique ID of the signature, usable in verification options and supported only for PDF documents. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | The type of text signature implementation. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | The signature type (`SignatureType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | The text of the signature. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | The horizontal alignment of text inside a signature, supported only for Image and Annotation signature implementations (see `TextSignatureImplementation` SignatureImplementation property). (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | The vertical alignment of text inside a signature. (inherited from [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | The Z-order position of the text signature, which determines the display order of overlapping signatures. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Pass the text and the QR code type to the constructor
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Put the QR code in the bottom right corner of the page
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Module color, background, and a dotted border with some space inside
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True

        signature.sign("signed.pdf", options)
```

### Guides
Task guides that use `QrCodeSignOptions`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
