---
title: "TextSignature क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "TextSignature क्लास टेक्स्ट हस्ताक्षर गुणों को शामिल करती है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

TextSignature क्लास टेक्स्ट हस्ताक्षर गुणों को शामिल करती है।

TextSignature प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | साइन या खोज ऑपरेशन से प्राप्त अद्वितीय हस्ताक्षर पहचानकर्ता के साथ TextSignature ऑब्जेक्ट को प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | Text Signature इंस्टेंस को क्लोन करता है। |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | निर्दिष्ट हस्ताक्षर की इस इंस्टेंस से समानता के लिए तुलना करता है। |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | सिग्नेचर के लिए हैश कोड लौटाता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | यह मूल एट्रिब्यूट दर्शाता है कि हस्ताक्षर दस्तावेज‑विशिष्ट है या नहीं। |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | टेक्स्ट सिग्नेचर कार्यान्वयन। |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | सिग्नेचर का टेक्स्ट। |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | सिग्नेचर निर्माण तिथि। ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) से विरासत में मिला है) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | यह संकेतक कि यह सिग्नेचर दस्तावेज़ से हटाया गया था या नहीं, दर्शाता है। ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) से विरासत में मिला है) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | सिग्नेचर की ऊँचाई। ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) से विरासत में मिला है) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | यह संकेतक कि यह घटक सिग्नेचर (`True`) है या दस्तावेज़ सामग्री (`False`)। ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) से विरासत में मिला है) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | हस्ताक्षर की बाएँ स्थिति। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | हस्ताक्षर संशोधन तिथि। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | हस्ताक्षर जहाँ पाया गया, उस पृष्ठ संख्या। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | हस्ताक्षर का अद्वितीय पहचानकर्ता, जो दस्तावेज़ में अपडेट या डिलीट ऑपरेशनों के माध्यम से हस्ताक्षर को संशोधित करने के लिए उपयोग किया जाता है। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | हस्ताक्षर का प्रकार। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | हस्ताक्षर की शीर्ष स्थिति। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | हस्ताक्षर की चौड़ाई। (विरासत में मिला [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### संबंधित देखें
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
