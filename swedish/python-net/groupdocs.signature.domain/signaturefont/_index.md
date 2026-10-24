---
title: "SignatureFont-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Klassen SignatureFont specificerar teckensnittsegenskaper för en textsignatur."
type: docs
url: /sv/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

Klassen SignatureFont specificerar teckensnittsegenskaper för en textsignatur.

SignatureFont-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | Initierar ett SignatureFont med standardvärden. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | Teckensnittets fetstil. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | Teckensnittets familjenamn. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | Teckensnittets kursiva stil. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | Teckensnittsstorlek. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | Teckensnittets genomstrykning. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | Understrykningsstil för teckensnittet. |

### Exempel

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
Uppgiftsguider som använder `SignatureFont`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
