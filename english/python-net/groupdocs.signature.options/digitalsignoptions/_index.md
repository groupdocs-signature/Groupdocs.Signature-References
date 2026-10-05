---
title: DigitalSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents the digital signature options."
type: docs
url: /python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Represents the digital signature options.

Learn more

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

The DigitalSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Initializes a new instance of the DigitalSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Initializes a new DigitalSignOptions instance with a certificate file. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Initializes a new DigitalSignOptions instance with a certificate stream. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Initializes a new instance of the DigitalSignOptions class with a certificate file and an appearance image file. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Initializes a new instance of DigitalSignOptions with a certificate file and an appearance image stream. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Initializes a new instance of DigitalSignOptions with a certificate stream and an appearance image file. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Initializes a new DigitalSignOptions instance with a certificate stream and an appearance image stream. |

### Methods
| Method | Description |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Clears internal resources. (inherited from [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Creates a new ImageSignOptions instance with a predefined image from a Base64 string. (inherited from [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Properties
| Property | Description |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | The flag that allows signing with a certificate whose validity period has ended. The default value is False; signing with an expired certificate raises `GroupDocsSignatureException` and the document is not signed. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | The flag that allows signing with a certificate whose validity period has not started yet. The default value is False; signing with such a certificate raises `GroupDocsSignatureException` and the document is not signed. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | The digital certificate file path. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | The digital certificate stream. If this property is specified it is always used instead of CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | The signature contact. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | The custom hash signing function used to sign the document, allowing users to implement their own digital signing logic. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | The height of the signature area on the document page in measure units (pixels, percents, or millimeters; see `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | The horizontal alignment of the image on a document page. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | The left X position of the signature area on the document page in measure units (pixels, percents, or millimeters as defined by `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | The signature location. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | The measure type (pixels, percents or millimeters) for the left and top properties. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | The space that is specified by default between the image and document edges (applies when horizontal or vertical alignment is specified). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | The margin measurement type (pixels, percents or millimeters). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | The password of the digital certificate. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | The reason of the signature. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | The rotation angle clockwise. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | The digital signature properties for the document. For PDF signing, advanced properties can be set using a [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/) instance. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | The measure type (pixels, percents or millimeters) for Width and Height properties. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | The stretch mode on the document page. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | The top Y position of the signature area on the document page in measure units (pixels, percents, or millimeters; see `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | The transparency of the digital signature, ranging from 0.0 to 1.0. Default is 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | The LTV (Long Term Validation) validation flag. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | The vertical alignment of the image on a document page. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | The visibility of the signature. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | The width of the signature area on the document page in measure values (pixels, percents, or millimeters). The measurement unit is defined by `MeasureType` via the SizeMeasureType property. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | The XAdES type. Default value is None (XAdES is off). |
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
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Pass the certificate and the appearance image to the constructor
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Show the signature on the page, at this position and size
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Information stored in the signature
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
Task guides that use `DigitalSignOptions`:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
