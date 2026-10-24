---
title: "TextSignature-klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "De TextSignature‑klasse bevat teksthandtekening‑eigenschappen."
type: docs
url: /nl/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

De TextSignature‑klasse bevat teksthandtekening‑eigenschappen.

Het TextSignature-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | Initialiseert een TextSignature‑object met de unieke handtekening‑identifier verkregen uit een onderteken‑ of zoekbewerking. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Kloont Text Signature‑instantie. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | Vergelijkt de opgegeven handtekening met deze instantie op gelijkheid. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | Retourneert de hashcode voor de handtekening. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | Het native‑attribuut dat aangeeft of de handtekening document‑specifiek is. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | De implementatie van de teksthandtekening. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | De tekst van de handtekening. |
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
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
