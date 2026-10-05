---
title: StampSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents the Stamp signature options."
type: docs
url: /python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

Represents the Stamp signature options.

Learn more:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

The StampSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | Initializes a new instance of the StampSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | Initializes a new instance of the StampSignOptions class with alignment options. |

### Methods
| Method | Description |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Clears internal resources. (inherited from [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Creates a new ImageSignOptions instance with a predefined image from a Base64 string. (inherited from [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Properties
| Property | Description |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | The background of the stamp. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | The background color crop type of the signature. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | The background image crop type of the signature. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | The height of the signature area on the document page in measure units (pixels, percents, or millimeters). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | The horizontal alignment of the image on a document page. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | The list of inner lines rendered as a set of rectangles. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | The left X position of the signature area on the document page in measure units (pixels, percents, or millimeters). See `MeasureType` `LocationMeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | The measure type (pixels, percents or millimeters) for the left and top properties. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | The space that is specified by default between the image and document edges (works if horizontal or vertical alignment is specified). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | The margin measurement type (pixels, percents or millimeters). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | The list of outer lines rendered as concentric circles. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | The rotation angle clockwise. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | The measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | The stamp type. Default is `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | The stretch mode on the document page. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | The top Y position of the signature area on the document page in measure units (pixels, percents, or millimeters). See `MeasureType` `LocationMeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | The transparency of the stamp signature. The value ranges from 0.0 to 1.0, with a default of 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | The vertical alignment of the stamp on a document page. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | The width of the signature area on the document page in measure values (pixels, percents, or millimeters). The measurement unit is defined by `MeasureType` SizeMeasureType. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | The signature will be placed on all document pages. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | The additional signature appearance. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | The border settings for the image signature. (inherited from [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | The document type of the signature options (`DocumentType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | The signature extensions. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | The hash algorithm to be used for cryptographic operations. Supported exclusively for digital signatures in PDF files. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | The file path of the signature image, used only if `image_stream` is not specified. (inherited from [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | The signature image stream. If specified, it is always used instead of ImageFilePath. (inherited from [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | The document page number for signing. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | The options to specify pages to be signed. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | The rectangle of area to put the image on document. (inherited from [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | The shape position defines where the shape should be presented in the document layout. Available only for Word documents. (inherited from [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | The signature type (`SignatureType`). (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | The Z-order position of the text signature, which determines the display order of overlapping signatures. (inherited from [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # configure additional stamp options as needed
    signature.sign(options)
```

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
