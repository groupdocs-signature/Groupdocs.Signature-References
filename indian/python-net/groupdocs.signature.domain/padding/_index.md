---
title: "Padding क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "तत्व से जुड़े पैडिंग या मार्जिन जानकारी को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/padding/
is_root: false
weight: 400
---


## Padding class

तत्व से जुड़े पैडिंग या मार्जिन जानकारी को दर्शाता है।

Padding प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/) | Padding क्लास का नया इंस्टेंस शून्य मानों के साथ आरंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#all) | Padding क्लास का नया इंस्टेंस सभी किनारों के लिए प्रदान किए गए पैडिंग आकार का उपयोग करके आरंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.domain/padding/__init__/#left-right-top-bottom) | Padding क्लास का नया इंस्टेंस प्रदान किए गए पैडिंग आकारों का उपयोग करके आरंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/padding/clone/) | इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [all](/signature/python-net/groupdocs.signature.domain/padding/all/) | सभी किनारों के लिए पैडिंग मान। |
| [bottom](/signature/python-net/groupdocs.signature.domain/padding/bottom/) | नीचे किनारे के लिए पैडिंग मान। |
| [horizontal](/signature/python-net/groupdocs.signature.domain/padding/horizontal/) | दाएँ और बाएँ किनारों के लिए संयुक्त पैडिंग। |
| [left](/signature/python-net/groupdocs.signature.domain/padding/left/) | बाएँ किनारे के लिए पैडिंग मान। |
| [right](/signature/python-net/groupdocs.signature.domain/padding/right/) | दाएँ किनारे के लिए पैडिंग मान। |
| [top](/signature/python-net/groupdocs.signature.domain/padding/top/) | ऊपर किनारे के लिए पैडिंग मान। |
| [vertical](/signature/python-net/groupdocs.signature.domain/padding/vertical/) | ऊपर और नीचे किनारों के लिए संयुक्त पैडिंग। |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [EMPTY](/signature/python-net/groupdocs.signature.domain/padding/empty/) | कोई पैडिंग नहीं वाले Padding ऑब्जेक्ट प्रदान करता है। |

### उदाहरण

```python
from groupdocs.signature.domain import Padding

# सभी पक्षों पर 5 इकाइयों की समान पैडिंग
uniform = Padding(5)

# दाएँ और नीचे की विशिष्ट पैडिंग
custom = Padding(right=40, bottom=60)
```

### Guides
`Padding` का उपयोग करने वाले टास्क गाइड:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### संबंधित देखें
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
