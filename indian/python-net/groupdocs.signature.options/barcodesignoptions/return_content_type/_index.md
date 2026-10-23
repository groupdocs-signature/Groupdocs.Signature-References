---
title: "return_content_type प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "जब returncontent प्रॉपर्टी सक्षम होती है, तब बारकोड सिग्नेचर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार।"
type: docs
url: /hi/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/
is_root: false
weight: 2120
---


## return_content_type property

`return_content` प्रॉपर्टी सक्षम होने पर बारकोड हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार।

डिफ़ॉल्ट रूप से यह `None` पर सेट होता है, जिसका अर्थ है कि बारकोड छवि सामग्री अपने मूल फ़ॉर्मेट में लौटाई जाती है। छवि फ़ॉर्मेट को [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature/format/) द्वारा निर्दिष्ट किया गया है। समर्थित मान हैं [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), और [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). यदि कोई असमर्थित फ़ॉर्मेट प्रदान किया जाता है, तो बारकोड छवि सामग्री PNG फ़ॉर्मेट में लौटाई जाएगी।

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
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
