---
title: "ImageSignature‑klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Klassen innehåller egenskaper för bildsignatur."
type: docs
url: /sv/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

Klassen innehåller egenskaper för bildsignatur.

ImageSignature‑typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | Initierar ett ImageSignature‑objekt med en unik signaturidentifierare som erhålls från Sign‑ eller Search‑metoden i klassen [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/). |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | Klona ImageSignature‑instansen. |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | Bestämmer om den angivna signaturen är lika med denna instans. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | Returnerar hashkoden för signaturen. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | Den binära bilddata för signaturen, i det format som anges av [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | Formatet för signaturbilden. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | Storleken i byte för signaturbilden. |
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
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
