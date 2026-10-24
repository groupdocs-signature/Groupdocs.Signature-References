---
title: "Border-klass"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Representerar kantutseende."
type: docs
url: /sv/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Representerar kantutseende.

Border-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Implementerar IClonable-gränssnittet. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | Kantfärgen för signaturen. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | Kantstilen för signaturen. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | Signaturens kanttransparens, varierar från 0.0 (opak) till 1.0 (klar), standardvärdet är 0 (opak). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | Kantens synlighet. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | Vikten på signaturens kant. |

### Exempel

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
Uppgiftsguider som använder `Border`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### Se även
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
