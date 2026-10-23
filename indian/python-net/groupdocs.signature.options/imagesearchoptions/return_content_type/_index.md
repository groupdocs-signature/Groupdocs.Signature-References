---
title: "return_content_type प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "जब returncontent प्रॉपर्टी सक्षम हो, तो लौटाए गए इमेज कंटेंट का फ़ाइल प्रकार।"
type: docs
url: /hi/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

`return_content` प्रॉपर्टी सक्षम होने पर लौटाए गए छवि सामग्री का फ़ाइल प्रकार।

यदि सेट नहीं किया गया (डिफ़ॉल्ट `None`), तो इमेज कंटेंट को उसके मूल फ़ॉर्मेट में लौटाया जाता है जैसा कि [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) में परिभाषित है। समर्थित मान हैं [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), और [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). यदि कोई असमर्थित फ़ॉर्मेट प्रदान किया जाता है, तो मूल फ़ॉर्मेट लौटाया जाता है।

### Definition:
```python
@property
def return_content_type(self):
    ...
@return_content_type.setter
def return_content_type(self, value):
    ...
```

### संबंधित देखें
* class [`ImageSearchOptions`](/signature/python-net/groupdocs.signature.options/imagesearchoptions/)
