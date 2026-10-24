---
title: "Border klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Stelt de weergave van de rand voor."
type: docs
url: /nl/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Stelt de weergave van de rand voor.

Het Border type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Implementeert IClonable interface. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | De randkleur van de handtekening. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | De stijl van de handtekeningrand. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | De transparantie van de handtekeningrand, variërend van 0.0 (ondoorzichtig) tot 1.0 (doorzichtig), standaard 0 (ondoorzichtig). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | De zichtbaarheid van de rand. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | De dikte van de handtekeningrand. |

### Voorbeeld

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
Taakgidsen die `Border` gebruiken:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### Zie ook
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
