---
title: "DigitalSearchOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिजिटल हस्ताक्षरों के लिए खोज विकल्प दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

डिजिटल हस्ताक्षरों के लिए खोज विकल्प दर्शाता है।

और अधिक जानें

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

DigitalSearchOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | DigitalSearchOptions क्लास का नया उदाहरण डिफ़ॉल्ट मानों के साथ प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | खोजने के लिए डिजिटल हस्ताक्षर की टिप्पणियाँ। |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | जब मान खाली न हो तो खोजने के लिए प्रमाणपत्र जारीकर्ता का विशिष्ट नाम। |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | खोजने के लिए डिजिटल हस्ताक्षर की तिथि और समय सीमा। nullable मान को अनदेखा किया जाएगा। |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | खोजने के लिए डिजिटल हस्ताक्षरों की तिथि और समय सीमा का अंत। null मान को अनदेखा किया जाएगा। |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | जब गैर‑खाली मान प्रदान किया जाए तो खोजने के लिए प्रमाणपत्र का विशिष्ट विषय नाम। |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | फ़्लैग जो संकेत करता है कि प्रत्येक दस्तावेज़ पृष्ठ पर खोज करनी है या नहीं। डिफ़ॉल्ट रूप से यह मान True है। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | खोज के लिए दस्तावेज़ पृष्ठ संख्या (वैकल्पिक)। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | फ़्लैग जो संकेत करता है कि दस्तावेज़ लेआउट में आकार की स्थिति लौटानी है या नहीं। केवल Word दस्तावेज़ों के लिए उपलब्ध। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | फ़्लैग जो केवल `IsSignature` के रूप में चिह्नित हस्ताक्षर लौटाता है। डिफ़ॉल्ट रूप से मान `False` है, जो दर्शाता है कि निर्दिष्ट मानदंड से मेल खाने वाले सभी हस्ताक्षर लौटाए जाते हैं। ([`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/) से विरासत में मिला) |

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
