---
title: "get_document_info मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दस्तावेज़ पृष्ठों की जानकारी प्राप्त करता है: उनका आकार, अधिकतम पृष्ठ ऊँचाई, अधिकतम ऊँचाई वाले पृष्ठ की चौड़ाई।"
type: docs
url: /hi/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

दस्तावेज़ पृष्ठों की जानकारी प्राप्त करता है: उनका आकार, अधिकतम पृष्ठ ऊँचाई, अधिकतम ऊँचाई वाले पृष्ठ की चौड़ाई।

हस्ताक्षरित दस्तावेज़ के बारे में अधिक जानें - फ़ाइल प्रकार, पृष्ठों की संख्या और कई अन्य फ़ॉर्मेट-विशिष्ट गुण:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### उदाहरण

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number 0-आधारित है: 0 पहला पृष्ठ है
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### संबंधित देखें
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
