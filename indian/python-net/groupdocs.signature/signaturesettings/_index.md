---
title: "SignatureSettings वर्ग"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "Signature व्यवहार को अनुकूलित करने के लिए सेटिंग्स का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

[`Signature`](/signature/python-net/groupdocs.signature/signature/) के व्यवहार को अनुकूलित करने के लिए सेटिंग्स का प्रतिनिधित्व करता है।

SignatureSettings प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | डिफ़ॉल्ट मानों के साथ एक डिफ़ॉल्ट SignatureSettings इंस्टेंस को प्रारंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Logger कार्यान्वयन के साथ एक डिफ़ॉल्ट SignatureSettings इंस्टेंस को प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | दस्तावेज़ प्रसंस्करण के दौरान उपयोग की जाने वाली डिफ़ॉल्ट संस्कृति। डिफ़ॉल्ट मान "en-US" है। |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | फ़्लैग जो यह दर्शाता है कि मानक दस्तावेज़ मेटाडेटा हस्ताक्षर जैसे Author, Owner, निर्माण तिथि, और संशोधित तिथि मेटाडेटा सूची में शामिल हैं या नहीं। |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | लॉग स्तर के फ़्लैग जो निर्धारित करते हैं कि कौन से प्रकार के संदेश [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) को पास किए जाते हैं। |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | लॉगिंग (Errors, Warnings, Traces) के लिए उपयोग किया गया लॉगर इम्प्लीमेंटेशन। [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | फ़्लैग जो निर्धारित करता है कि जब Delete मेथड के पास हटाने के लिए कोई प्रभावित हस्ताक्षर नहीं होते हैं तो स्रोत दस्तावेज़ को पुनः‑सहेजा जाए या नहीं। |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | फ़्लैग जो निर्धारित करता है कि जब `Update` मेथड के पास अपडेट करने के लिए कोई हस्ताक्षर नहीं होते हैं तो स्रोत दस्तावेज़ को पुनः‑सहेजा जाए या नहीं। |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | फ़्लैग जो निर्धारित करता है कि हटाए गए हस्ताक्षर दस्तावेज़ जानकारी परिणाम में शामिल हों या नहीं। प्रत्येक [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) में एक `Deleted` फ़्लैग होता है जो यह दर्शाता है कि वह हटाया गया था। |

### संबंधित देखें
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
