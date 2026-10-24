---
title: "Padding‑klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar utfyllnads- eller marginalinformation som är associerad med elementet."
type: docs
url: /sv/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

Representerar utfyllnads- eller marginalinformation som är associerad med elementet.

Padding‑typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Initierar en ny instans av Padding‑klassen med nollvärden. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Initierar en ny instans av Padding‑klassen med den angivna utfyllnadsstorleken för alla kanter. |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Initierar en ny instans av Padding‑klassen med de angivna utfyllnadsstorlekarna. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | Hämtar en kopia av detta objekt. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | Utfyllnadsvärdet för alla kanter. |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | Utfyllnadsvärdet för den nedre kanten. |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | Den kombinerade utfyllnaden för högra och vänstra kanterna. |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | Utfyllnadsvärdet för den vänstra kanten. |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | Utfyllnadsvärdet för den högra kanten. |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | Utfyllnadsvärdet för den övre kanten. |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | Den kombinerade utfyllnaden för övre och nedre kanterna. |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | Tillhandahåller ett Padding‑objekt utan utfyllnad. |

### Exempel

```python
from groupdocs.signature.domain import Padding

# Enhetlig utfyllnad på 5 enheter på alla sidor
uniform = Padding(5)

# Specifik utfyllnad på höger och botten
custom = Padding(right=40, bottom=60)
```

### Guides
Uppgiftsguider som använder `Padding`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
