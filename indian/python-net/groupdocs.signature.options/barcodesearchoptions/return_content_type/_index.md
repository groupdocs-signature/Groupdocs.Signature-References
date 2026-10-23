---
title: "return_content_type प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "जब returncontent प्रॉपर्टी सक्षम हो, Barcode सिग्नेचर के लिए लौटाए गए इमेज कंटेंट का फ़ाइल प्रकार।"
type: docs
url: /hi/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/
is_root: false
weight: 2040
---


## return_content_type property

`return_content` प्रॉपर्टी सक्षम होने पर बारकोड हस्ताक्षर के लिए लौटाई गई इमेज सामग्री का फ़ाइल प्रकार।

डिफ़ॉल्ट रूप से यह None है, जो बारकोड इमेज को उसके मूल फ़ॉर्मेट में लौटाता है जैसा कि [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) द्वारा निर्दिष्ट है।

समर्थित मान हैं [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), और [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). यदि इनके अलावा कोई मान प्रदान किया जाता है, तो इमेज PNG फ़ॉर्मेट में लौटाई जाएगी।

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
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
