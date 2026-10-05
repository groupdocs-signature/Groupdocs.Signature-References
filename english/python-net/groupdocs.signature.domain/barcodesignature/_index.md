---
title: BarcodeSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents a barcode signature."
type: docs
url: /python-net/groupdocs.signature.domain/barcodesignature/
is_root: false
weight: 20
---


## BarcodeSignature class

Represents a barcode signature.

The BarcodeSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/barcodesignature/__init__/#signature_id) | Initializes a BarcodeSignature object with a signature identifier obtained after a search process. The identifier is used to retrieve additional properties for this signature from the document's signature information layer. |

### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/barcodesignature/clone/) | Clones Barcode Signature instance. |
| [equals](/signature/python-net/groupdocs.signature.domain/barcodesignature/equals/#obj) | Compares this barcode signature with another signature for equality. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/barcodesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/barcodesignature/get_hash_code/) | Returns the hash code for the barcode signature. |

### Properties
| Property | Description |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/barcodesignature/content/) | The barcode binary data image content in the format specified by [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/). |
| [encode_type](/signature/python-net/groupdocs.signature.domain/barcodesignature/encode_type/) | The barcode encode type. |
| [format](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) | The format of the barcode signature image. |
| [text](/signature/python-net/groupdocs.signature.domain/barcodesignature/text/) | The text of the barcode. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | The signature creation date. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | The flag indicating whether this signature was deleted from the document. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | The height of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | The flag indicating whether this component represents a signature (`True`) or document content (`False`). (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | The left position of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | The signature modification date. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | The page number where the signature was found. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | The unique identifier of the signature, used to modify the signature in the document via update or delete operations. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | The type of signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | The top position of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | The width of the signature. (inherited from [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Guides
Task guides that use `BarcodeSignature`:

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### See Also
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
