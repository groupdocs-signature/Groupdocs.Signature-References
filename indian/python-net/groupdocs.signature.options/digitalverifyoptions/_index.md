---
title: "DigitalVerifyOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "दस्तावेज़ के डिजिटल हस्ताक्षर को सत्यापित करने के विकल्प रखता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

दस्तावेज़ के डिजिटल हस्ताक्षर को सत्यापित करने के विकल्प रखता है।

और अधिक जानें

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

DigitalVerifyOptions प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | डिफ़ॉल्ट मानों के साथ DigitalVerifyOptions का एक इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | दिए गए डिजिटल प्रमाणपत्र फ़ाइल पथ के साथ DigitalVerifyOptions का एक इंस्टेंस इनिशियलाइज़ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | दिए गए प्रमाणपत्र स्ट्रीम के साथ DigitalVerifyOptions का एक इंस्टेंस इनिशियलाइज़ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | प्रमाणपत्र फ़ाइल पथ या स्ट्रीम से प्राप्त X509Certificate2 प्रमाणपत्र। |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | डिजिटल प्रमाणपत्र का फ़ाइल पथ। |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | डिजिटल प्रमाणपत्र की स्ट्रीम। |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | मान्य करने के लिए डिजिटल सिग्नेचर की टिप्पणियाँ। |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | मान्य करने के लिए सिग्नेचर संपर्क। |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | मान्य करने के लिए प्रमाणपत्र का जारीकर्ता नाम। |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | मान्य करने के लिए सिग्नेचर स्थान। |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | यदि आवश्यक हो तो डिजिटल प्रमाणपत्र का पासवर्ड। |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | मान्य करने के लिए डिजिटल सिग्नेचर का कारण। |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | मान्य करने के लिए डिजिटल सिग्नेचर की तिथि और समय सीमा की शुरुआत। None मान को अनदेखा किया जाएगा। |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | मान्य करने के लिए डिजिटल सिग्नेचर की तिथि और समय सीमा का अंत। null मान को अनदेखा किया जाएगा। |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | मान्य करने के लिए प्रमाणपत्र का subject distinguished name; सत्यापन जांचता है कि सिग्नेचर का subject name इस केस‑सेंसिटिव मान को शामिल करता है या बराबर है। |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | यह फ़्लैग दर्शाता है कि क्या प्रत्येक दस्तावेज़ पेज की जाँच की जानी चाहिए। डिफ़ॉल्ट रूप से मान True है। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | वैकल्पिक सिग्नेचर विकल्पों की जाँच के लिए अतिरिक्त एक्सटेंशन। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | वैध प्रॉपर्टी फ़्लैग। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | जाँच के लिए दस्तावेज़ पेज संख्या; यदि सेट नहीं है, तो दस्तावेज़ के सभी पेज पहली घटना के लिए जाँचे जाते हैं (न्यूनतम मान 1 है)। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | जाँच के लिए पेज निर्दिष्ट करने के पेज विकल्प। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | हेडर/फ़ूटर में सिग्नेचर की जाँच के लिए दस्तावेज़ लेआउट में शैप की स्थिति। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
