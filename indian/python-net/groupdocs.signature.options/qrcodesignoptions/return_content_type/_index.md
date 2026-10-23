---
title: "return_content_type प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "जब returncontent प्रॉपर्टी सक्षम हो, तो QR‑Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार।"
type: docs
url: /hi/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/
is_root: false
weight: 2160
---


## return_content_type property

`return_content` गुण सक्षम होने पर QR‑Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार।

डिफ़ॉल्ट रूप से यह `None` है, जो QR‑Code छवि सामग्री को उसके मूल फ़ॉर्मेट में लौटाता है जैसा कि [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) द्वारा निर्दिष्ट किया गया है।

समर्थित मान हैं [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), और [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/). यदि कोई असमर्थित फ़ॉर्मेट दिया जाता है, तो सामग्री PNG फ़ॉर्मेट में लौटाई जाती है।

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
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
