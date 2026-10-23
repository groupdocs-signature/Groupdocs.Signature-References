---
title: "Border क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "सीमा की उपस्थिति को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

सीमा की उपस्थिति को दर्शाता है।

Border प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | IClonable इंटरफ़ेस को लागू करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | सिग्नेचर की बॉर्डर रंग। |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | सिग्नेचर बॉर्डर शैली। |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | सिग्नेचर बॉर्डर पारदर्शिता, 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक, डिफ़ॉल्ट 0 (अपारदर्शी) है। |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | बॉर्डर की दृश्यता। |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | सिग्नेचर बॉर्डर का वजन। |

### उदाहरण

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
`Border` का उपयोग करने वाले टास्क गाइड:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### संबंधित देखें
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
