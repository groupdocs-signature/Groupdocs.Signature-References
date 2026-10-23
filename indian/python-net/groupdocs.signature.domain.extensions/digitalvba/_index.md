---
title: "DigitalVBA क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "स्प्रेडशीट VBA प्रोजेक्ट्स के लिए डिजिटल सिग्नेचर दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

स्प्रेडशीट VBA प्रोजेक्ट्स के लिए डिजिटल सिग्नेचर दर्शाता है।

`Xlsm` या `Xltm` जैसे स्प्रेडशीट दस्तावेज़ फ़ॉर्मेट में VBA प्रोजेक्ट पर हस्ताक्षर करने की क्षमता प्रदान करता है। यदि कई [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) एक्सटेंशन को [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/) में जोड़ा जाता है, तो साइनिंग के दौरान केवल पहला उपयोग किया जाता है।

DigitalVBA प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | डिजिटलVBA क्लास का नया इंस्टेंस प्रमाणपत्र फ़ाइल के साथ इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | डिजिटलVBA क्लास का नया इंस्टेंस प्रमाणपत्र स्ट्रीम के साथ इनिशियलाइज़ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है। (इनहेरिटेड from [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### गुण
| गुण | विवरण |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | डिजिटल प्रमाणपत्र फ़ाइल पथ, केवल तब उपयोग किया जाता है जब `CertificateStream` निर्दिष्ट नहीं किया गया हो। |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | डिजिटल प्रमाणपत्र स्ट्रीम। यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा CertificateFilePath के बजाय उपयोग किया जाता है। |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | हस्ताक्षर टिप्पणी। |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | डिजिटल प्रमाणपत्र का पासवर्ड। |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | वह सेटिंग जो निर्धारित करती है कि केवल VBA प्रोजेक्ट साइन किया जाए या नहीं। जब True हो, तो स्प्रेडशीट दस्तावेज़ स्वयं साइन नहीं होता; केवल VBA प्रोजेक्ट साइन होता है। |

### उदाहरण

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # स्प्रेडशीट के भीतर मैक्रो साइन करें
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # VBA प्रोजेक्ट को डिजिटल रूप से साइन करने के लिए एक्सटेंशन जोड़ें
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # सुनिश्चित करें कि VBA प्रोजेक्ट सिग्नेचर भाग जोड़ा गया है
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### संबंधित देखें
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
