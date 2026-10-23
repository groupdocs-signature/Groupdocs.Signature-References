---
title: "CertificateVerifyOptions वर्ग"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "सर्टिफिकेट दस्तावेज़ों को सत्यापित करने के विकल्प रखता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

सर्टिफिकेट दस्तावेज़ों को सत्यापित करने के विकल्प रखता है।

और अधिक जानें

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

CertificateVerifyOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | TextVerifyOptions का एक नया उदाहरण डिफ़ॉल्ट मानों के साथ आरंभ करता है। |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | वेरिफ़ाई करने के लिए विषय के साथ एक नया CertificateVerifyOptions इंस्टेंस प्रारंभ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | यह प्रॉपर्टी वैधता परिणाम के आधार पर यह दर्शाती है कि प्रमाणपत्र समाप्त हो गया है या नहीं। |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | वेरिफ़ाई करने के लिए प्रमाणपत्र जारीकर्ता। |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | वेरिफ़िकेशन के लिए उपयोग किया गया टेक्स्ट मैच प्रकार। |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | वेरिफ़िकेशन प्रक्रिया को बेसिक वैधता नीति का उपयोग करके X.509 चेन वैधता प्रदान करनी चाहिए। |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | वेरिफ़ाई करने के लिए प्रमाणपत्र सीरियल नंबर। |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | वेरिफ़ाई करने के लिए प्रमाणपत्र विषय। |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | वेरिफ़ाई करने के लिए प्रमाणपत्र थंबप्रिंट। |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | यह फ़्लैग दर्शाता है कि क्या प्रत्येक दस्तावेज़ पेज की जाँच की जानी चाहिए। डिफ़ॉल्ट रूप से मान True है। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | वैकल्पिक सिग्नेचर विकल्पों की जाँच के लिए अतिरिक्त एक्सटेंशन। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | वैध प्रॉपर्टी फ़्लैग। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | जाँच के लिए दस्तावेज़ पेज संख्या; यदि सेट नहीं है, तो दस्तावेज़ के सभी पेज पहली घटना के लिए जाँचे जाते हैं (न्यूनतम मान 1 है)। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | जाँच के लिए पेज निर्दिष्ट करने के पेज विकल्प। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | हेडर/फ़ूटर में सिग्नेचर की जाँच के लिए दस्तावेज़ लेआउट में शैप की स्थिति। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
