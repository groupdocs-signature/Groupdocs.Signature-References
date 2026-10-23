---
title: "ImageDigitalVerifyOptions क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "रास्टर इमेज़ में डिजिटल सिग्नेचर को सत्यापित करने के विकल्पों को रखता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

रास्टर इमेज़ में डिजिटल सिग्नेचर को सत्यापित करने के विकल्पों को रखता है।

ImageDigitalVerifyOptions प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | रास्टर इमेज में डिजिटल (स्टेगनोग्राफी) सिग्नेचर की जाँच के लिए ImageDigitalVerifyOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

### गुण
| गुण | विवरण |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | AnalyzePercentageDigitalSignature द्वारा लौटाई गई संभावना (0-100)। |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | आंशिक निष्कर्षण के लिए डिटेक्शन थ्रेशोल्ड प्रतिशत (0-100)। डिफ़ॉल्ट 75 है। |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | सिग्नेचर एम्बेड करने के लिए उपयोग किया गया पासवर्ड। |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | यह प्रॉपर्टी निर्धारित करती है कि अधिकतम सटीकता के लिए पूर्ण डेटा एक्सट्रैक्शन (AnalyzePercentageDigitalSignature) किया जाए या नहीं। |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | यह फ़्लैग दर्शाता है कि क्या प्रत्येक दस्तावेज़ पेज की जाँच की जानी चाहिए। डिफ़ॉल्ट रूप से मान True है। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | वैकल्पिक सिग्नेचर विकल्पों की जाँच के लिए अतिरिक्त एक्सटेंशन। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | वैध प्रॉपर्टी फ़्लैग। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | जाँच के लिए दस्तावेज़ पेज संख्या; यदि सेट नहीं है, तो दस्तावेज़ के सभी पेज पहली घटना के लिए जाँचे जाते हैं (न्यूनतम मान 1 है)। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | जाँच के लिए पेज निर्दिष्ट करने के पेज विकल्प। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | हेडर/फ़ूटर में सिग्नेचर की जाँच के लिए दस्तावेज़ लेआउट में शैप की स्थिति। ([`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/) से विरासत में मिला) |

### संबंधित देखें
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
