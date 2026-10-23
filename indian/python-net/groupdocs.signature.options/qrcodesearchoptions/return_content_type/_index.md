---
title: "return_content_type प्रॉपर्टी"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "जब returncontent प्रॉपर्टी सक्षम हो तो QR‑कोड हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार।"
type: docs
url: /hi/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/
is_root: false
weight: 2050
---


## return_content_type property

`return_content` प्रॉपर्टी सक्षम होने पर QR-Code हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार।

डिफ़ॉल्ट रूप से इसे `None` पर सेट किया जाता है, जो QR‑कोड छवि सामग्री को उसके मूल स्वरूप में लौटाता है। छवि स्वरूप को यहाँ निर्दिष्ट किया गया है: [`QrCodeSignature.Format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/)। समर्थित मान हैं [`FileType.JPEG`](/signature/python-net/groupdocs.signature.domain/filetype/jpeg/), [`FileType.PNG`](/signature/python-net/groupdocs.signature.domain/filetype/png/), और [`FileType.BMP`](/signature/python-net/groupdocs.signature.domain/filetype/bmp/)। यदि कोई असमर्थित स्वरूप प्रदान किया जाता है, तो QR‑कोड छवि सामग्री PNG के रूप में लौटाई जाती है।

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
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
