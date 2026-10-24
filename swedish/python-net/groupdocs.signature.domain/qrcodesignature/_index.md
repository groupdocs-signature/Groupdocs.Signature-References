---
title: "QrCodeSignature-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar QR‑kod‑signaturegenskaper."
type: docs
url: /sv/python-net/groupdocs.signature.domain/qrcodesignature/
is_root: false
weight: 550
---


## QrCodeSignature class

Representerar QR‑kod‑signaturegenskaper.

QrCodeSignature-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/qrcodesignature/__init__/#signature_id) | Initierar ett QrCodeSignature-objekt med en signaturidentifierare som erhållits efter en sökprocess. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/qrcodesignature/clone/) | Klonar QR-Code-signaturinstans. |
| [equals](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals/#obj) | Bestämmer om det givna signaturobjektet är lika med denna instans. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals_object/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/#data_encryption) |  |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data_idata_encryption/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_hash_code/) | Åsidosätter GetHashCode‑metoden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/qrcodesignature/content/) | QR-kodens binära bilddata av typen [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). |
| [encode_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/encode_type/) | QR-kodens kodningstyp. |
| [format](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) | Formatet för QR-kodsignaturens bild. |
| [text](/signature/python-net/groupdocs.signature.domain/qrcodesignature/text/) | Texten för QR-koden. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Signaturens skapelsedatum. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Flaggan som indikerar om denna signatur har raderats från dokumentet. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Signaturens höjd. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Flaggan som indikerar om denna komponent representerar en signatur (`True`) eller dokumentinnehåll (`False`). (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Signaturens vänstra position. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Signaturens ändringsdatum. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Sidnumret där signaturen hittades. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Den unika identifieraren för signaturen, som används för att ändra signaturen i dokumentet via uppdaterings‑ eller raderingsoperationer. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Signaturens typ. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Signaturens övre position. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Signaturens bredd. (ärvd från [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    if result.signatures:
        qr = result.signatures[0]
        print(qr.text, qr.encode_type.type_name, qr.left, qr.top)
```

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
