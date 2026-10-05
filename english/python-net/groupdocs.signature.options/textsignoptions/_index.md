---
title: TextSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents the Text signature options."
type: docs
url: /python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Represents the Text signature options.

Learn more

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

The TextSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Initializes a new instance of the TextSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Initializes a new instance of the TextSignOptions class with text. |

### Properties
| Property | Description |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | The signature background settings. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | The border settings. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | The font of the signature. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | The fore color of the signature. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | The title of the text form field to place the text signature into. Can be used only when `signature_implementation` is set to `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | The type of form field to place the text signature into. This property is applicable only when `signature_implementation` is set to `TextSignatureImplementation.FORM_FIELD` (i.e., TextToFormField). The default value is `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | The height of the signature on the document page in measure values (pixels, percents, or millimeters). The unit is determined by the `SizeMeasureType` property. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | The horizontal alignment of the signature on the document page. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | The left X position of the signature on the document page in measure values (pixels, percents, or millimeters as defined by `MeasureType` LocationMeasureType property). Works if horizontal alignment is not specified. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | The measure type (pixels, percents or millimeters) for `left` and `top` properties. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | The space between the signature and the document edges. Applies only when horizontal or vertical alignment is specified. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | The measure type (pixels, percents or millimeters) for the margin. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | The native attribute. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | The rotation angle of the signature on the document page (clockwise). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | The shape position defines where the shape should be presented in the document layout. Available only for Word documents. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | The type of shape to put text. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | The unique ID of the signature, usable in verification options and supported only for PDF documents. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | The type of text signature implementation. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | The measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | The stretch mode on document page. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | The text of the signature. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | The horizontal alignment of text inside a signature, supported only for Image and Annotation signature implementations (see `TextSignatureImplementation` SignatureImplementation property). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | The vertical alignment of text inside a signature. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | The top Y position of the signature on the document page, expressed in measurement units (pixels, percent, or millimeters). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | The signature transparency, a float between 0.0 (opaque) and 1.0 (clear). Default is 0.0 (opaque). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | The vertical alignment of the signature on the document page. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | The width of the signature on the document page in measure values (pixels, percents, or millimeters; see `MeasureType` `SizeMeasureType` property). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | The signature will be placed on all document pages. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | The additional signature appearance. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | The document type of the signature options (`DocumentType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | The signature extensions. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | The hash algorithm to be used for cryptographic operations. Supported exclusively for digital signatures in PDF files. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | The document page number for signing. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | The options to specify pages to be signed. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | The signature type (`SignatureType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | The Z-order position of the text signature, which determines the display order of overlapping signatures. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Task guides that use `TextSignOptions`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
