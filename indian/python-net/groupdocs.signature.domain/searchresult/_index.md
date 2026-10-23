---
title: "SearchResult क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "निर्दिष्ट दस्तावेज़ में हस्ताक्षरों की खोज के परिणाम का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

निर्दिष्ट दस्तावेज़ में हस्ताक्षरों की खोज के परिणाम का प्रतिनिधित्व करता है।

SearchResult प्रकार निम्नलिखित सदस्य उजागर करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | सर्च परिणामों पर एक इटररेटर लौटाता है। |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### गुण
| गुण | विवरण |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | डेस्टिनेशन दस्तावेज़ का आकार, जो सर्च मेथड के लिए हमेशा 0 होता है। |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | सर्च मानदंड द्वारा सर्च प्रक्रिया में विफल हुई हस्ताक्षरों की सूची [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)। |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | सर्च प्रक्रिया का निष्पादन समय मिलीसेकंड में। |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | पाए गए हस्ताक्षरों की सूची [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)। |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | स्रोत दस्तावेज़ का आकार। |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | पाए गए हस्ताक्षरों की सूची ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | सर्च प्रक्रिया द्वारा लौटाए गए प्रोसेस किए गए हस्ताक्षरों की कुल संख्या। |

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### संबंधित देखें
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
