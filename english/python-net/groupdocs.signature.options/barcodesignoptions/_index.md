---
title: BarcodeSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents the barcode signature options."
type: docs
url: /python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

Represents the barcode signature options.

Learn more

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

The BarcodeSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | Initializes a new instance of the BarcodeSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | Initializes a new instance of the BarcodeSignOptions class with text. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | Initializes a new instance of the BarcodeSignOptions class with text. |

### Properties
| Property | Description |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | The alignment of text in the resulting barcode image. Default value is None. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | The barcode type. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | The foreground color of the barcode bars; using it may cause verification problems, so use it carefully. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | The height of the signature area on the document page in measure units (pixels, percents, or millimeters). See `MeasureType` for size measure type. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | The horizontal alignment of the image on a document page. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | The space between barcode elements and result image borders. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | The left X position of the signature area on the document page, expressed in measurement units (pixels, percents, or millimeters). See `MeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | The measure type (pixels, percents or millimeters) for left and top properties. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | The space that is specified by default between the image and document edges (applies when horizontal or vertical alignment is set). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | The margin measurement type (pixels, percents or millimeters). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | The flag indicating whether to retrieve the barcode image content of a signature placed on a document page. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | The file type of the returned image content of the Barcode signature when the `return_content` property is enabled. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | The rotation angle clockwise. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | The measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | The stretch mode on the document page. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | The top Y position of the signature area on the document page in measure units (pixels, percents, or millimeters). See `MeasureType` LocationMeasureType. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | The transparency of the barcode signature, ranging from 0.0 (fully opaque) to 1.0 (fully transparent); default is 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | The vertical alignment of the barcode image on a document page. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | The width of the signature area on the document page in measure values (pixels, percents, or millimeters) as defined by `MeasureType`. |
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
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
Task guides that use `BarcodeSignOptions`:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
