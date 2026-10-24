---
title: "TextSignature-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Klassen TextSignature innehåller textsignatur‑egenskaper."
type: docs
url: /sv/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

Klassen TextSignature innehåller textsignatur‑egenskaper.

TextSignature-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | Initierar ett TextSignature-objekt med den unika signaturidentifieraren som erhölls från en signerings- eller sökoperation. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Klonar Text Signature-instans. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | Jämför den angivna signaturen med denna instans för likhet. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | Returnerar hashkoden för signaturen. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | Det inbyggda attributet som indikerar om signaturen är dokumentspecifik. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | Implementeringen av textsignaturen. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | Texten i signaturen. |
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
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
