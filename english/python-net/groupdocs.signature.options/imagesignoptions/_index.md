---
title: ImageSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents the Image signature options."
type: docs
url: /python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Represents the Image signature options.

Learn more:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

The ImageSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Initializes a new instance of the ImageSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Initializes ImageSignOptions with an image file. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Initializes a new ImageSignOptions instance with an image stream. |

### Methods
| Method | Description |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Clears internal resources. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Creates a new ImageSignOptions instance with a predefined image from a Base64 string. |

### Properties
| Property | Description |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | The border settings for the image signature. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | The height of the signature on the document page in measure values (pixels, percents, or millimeters; see `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | The horizontal alignment of the signature on the document page. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | The file path of the signature image, used only if `image_stream` is not specified. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | The signature image stream. If specified, it is always used instead of ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | The left X position of the signature on the document page in measure values (pixels, percents, or millimeters). Works if horizontal alignment is not specified. See `MeasureType` for location measure type. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | The measure type (pixels, percents or millimeters) for left and top properties. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | The space between the signature and the document edges. Works only if horizontal or vertical alignment are specified. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | The measure type (pixels, percents or millimeters) for the margin. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | The rectangle of area to put the image on document. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | The rotation angle of the signature on the document page (clockwise). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | The shape position defines where the shape should be presented in the document layout. Available only for Word documents. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | The measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | The stretch mode on the document page. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | The top Y position of the signature on the document page in measure values (pixels, percents, or millimeters) as defined by `MeasureType` LocationMeasureType. Works if vertical alignment is not specified. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | The signature transparency, ranging from 0.0 (opaque) to 1.0 (clear), defaults to 0 (opaque). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | The vertical alignment of the signature on the document page. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | The width of the signature on the document page in measure values (pixels, percents, or millimeters `MeasureType` size measure type). |
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
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Create image signature options with the image file
        options = ImageSignOptions("signature.jpg")
        # Set signature position and size
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Task guides that use `ImageSignOptions`:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
