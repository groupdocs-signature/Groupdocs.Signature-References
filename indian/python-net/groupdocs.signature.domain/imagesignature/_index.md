---
title: "ImageSignature क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "यह क्लास इमेज सिग्नेचर गुणों को शामिल करती है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

यह क्लास इमेज सिग्नेचर गुणों को शामिल करती है।

ImageSignature प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/) क्लास के Sign या Search मेथड से प्राप्त अद्वितीय हस्ताक्षर पहचानकर्ता के साथ एक ImageSignature ऑब्जेक्ट को प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | ImageSignature इंस्टेंस को क्लोन करें। |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | निर्धारित करता है कि निर्दिष्ट हस्ताक्षर इस इंस्टेंस के बराबर है या नहीं। |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | सिग्नेचर के लिए हैश कोड लौटाता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | हस्ताक्षर का बाइनरी इमेज डेटा, वह फ़ॉर्मेट जिसमें [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) द्वारा निर्दिष्ट किया गया है। |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | हस्ताक्षर इमेज का फ़ॉर्मेट। |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | हस्ताक्षर इमेज का बाइट्स में आकार। |
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
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### संबंधित देखें
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
