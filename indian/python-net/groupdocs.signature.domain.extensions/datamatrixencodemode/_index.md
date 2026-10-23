---
title: "DataMatrixEncodeMode क्लास"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "DataMatrixEncodeMode enum — GroupDocs.Signature for Python via .NET API संदर्भ।"
type: docs
url: /hi/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

DataMatrixEncodeMode प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | DataMatrix एन्कोडिंग के लिए सर्वोत्तम एन्कोड मोड को स्वचालित रूप से चुनें |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | प्रति बाइट एक अल्फ़ान्यूमेरिक या दो संख्यात्मक अक्षरों को एन्कोड करता है |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | 8 बिट मानों को एन्कोड करें |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding में निर्दिष्ट एन्कोडिंग के साथ एन्कोड करें |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | C40 एन्कोडिंग का उपयोग करता है। अपर केस अल्फ़ान्यूमेरिक, लोअर केस और विशेष वर्णों को एन्कोड करता है |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | टेक्स्ट एन्कोडिंग का उपयोग करता है। लोअर केस अल्फ़ान्यूमेरिक, अपर केस और विशेष वर्णों को एन्कोड करता है। |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | EDIFACT एन्कोडिंग का उपयोग करता है। प्रत्येक वर्ण के लिए छह बिट्स का उपयोग करता है, अंकों, अपर केस अक्षरों और कई विराम चिह्नों को एन्कोड करता है, लेकिन लोअर केस अक्षरों का समर्थन नहीं करता। |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | ANSI X12 एन्कोडिंग का उपयोग करता है। |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | ExtendedCodetext मोड कोड-टेक्स्ट में एन्कोडिंग योजनाओं को मैन्युअल रूप से स्विच करने की अनुमति देता है। स्वरूप : "\\Encodation_scheme_name:text\\Encodation_scheme_name:text"। अनुमत एन्कोडिंग योजनाएँ हैं: EDIFACT, ANSIX12, ASCII, C40, Text, Auto। विस्तारित कोड-टेक्स्ट उदाहरण: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText" सभी बैकस्लैश (\\) को टेक्स्ट में दोहरा होना चाहिए। |

### संबंधित देखें
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
