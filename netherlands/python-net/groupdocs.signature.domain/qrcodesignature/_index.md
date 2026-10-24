---
title: "QrCodeSignature klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt QR-code handtekeningeigenschappen voor."
type: docs
url: /nl/python-net/groupdocs.signature.domain/qrcodesignature/
is_root: false
weight: 550
---


## QrCodeSignature class

Stelt QR-code handtekeningeigenschappen voor.

De QrCodeSignature type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/qrcodesignature/__init__/#signature_id) | Initialiseert een QrCodeSignature object met een handtekeningidentificatie verkregen na een zoekproces. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/qrcodesignature/clone/) | Kloont QR-Code Signature instantie. |
| [equals](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals/#obj) | Bepaalt of het gegeven handtekeningobject gelijk is aan deze instantie. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals_object/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/#data_encryption) |  |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data_idata_encryption/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_hash_code/) | Overschrijft de GetHashCode-methode. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/qrcodesignature/content/) | De QR-code binaire data afbeeldinginhoud van type [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). |
| [encode_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/encode_type/) | Het QR-code encode type. |
| [format](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) | Het formaat van de QR-code handtekeningafbeelding. |
| [text](/signature/python-net/groupdocs.signature.domain/qrcodesignature/text/) | De tekst van de QR-code. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | De datum van handtekeningcreatie. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | De vlag die aangeeft of deze handtekening uit het document is verwijderd. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | De hoogte van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | De vlag die aangeeft of dit component een handtekening (`True`) of documentinhoud (`False`) vertegenwoordigt. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | De linkse positie van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | De wijzigingsdatum van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Het paginanummer waarop de handtekening werd gevonden. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | De unieke identificatie van de handtekening, gebruikt om de handtekening in het document te wijzigen via update- of delete-bewerkingen. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Het type handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | De bovenste positie van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | De breedte van de handtekening. (geërfd van [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    if result.signatures:
        qr = result.signatures[0]
        print(qr.text, qr.encode_type.type_name, qr.left, qr.top)
```

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
