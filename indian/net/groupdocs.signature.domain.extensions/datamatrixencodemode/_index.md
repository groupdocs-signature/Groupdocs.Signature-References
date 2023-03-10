---
title: DataMatrixEncodeMode
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: डेटमैट्रक्स एनकडर क एन्कडंग मड ऑट के लए डफ़ल्ट
type: docs
weight: 220
url: /hi/net/groupdocs.signature.domain.extensions/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

डेटामैट्रिक्स एनकोडर का एन्कोडिंग मोड, ऑटो के लिए डिफ़ॉल्ट

```csharp
public enum DataMatrixEncodeMode
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Auto | `0` | डेटामैट्रिक्स एन्कोडिंग के लिए स्वचालित रूप से सर्वश्रेष्ठ एन्कोड मोड चुनें |
| ASCII | `1` | प्रति बाइट एक अल्फ़ान्यूमेरिक या दो न्यूमेरिक वर्णों को एन्कोड करता है |
| Full | `6` | 8 बिट मानों को एनकोड करें |
| Custom | `7` | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding में निर्दिष्ट एन्कोडिंग के साथ एनकोड करें |
| C40 | `8` | C40 एन्कोडिंग का उपयोग करता है। अपर-केस अल्फ़ान्यूमेरिक, लोअर केस और स्पेशल कैरेक्टर्स को एनकोड करता है |
| Text | `9` | टेक्स्ट एन्कोडिंग का उपयोग करता है। लोअर-केस अल्फ़ान्यूमेरिक, अपर केस और विशेष वर्णों को एनकोड करता है। |
| EDIFACT | `10` | EDIFACT एन्कोडिंग का उपयोग करता है। प्रति वर्ण छह बिट्स का उपयोग करता है, अंकों को एन्कोड करता है, अपर-केस अक्षर, और कई विराम चिह्न, लेकिन लोअर-केस अक्षरों के लिए कोई समर्थन नहीं है। |
| ANSIX12 | `11` | ANSI X12 एन्कोडिंग का उपयोग करता है। |
| ExtendedCodetext | `12` | एक्सटेंडेडकोडटेक्स्ट मोड कोड-टेक्स्ट में एन्कोडिंग योजनाओं को मैन्युअल रूप से स्विच करने की अनुमति देता है। प्रारूप: "\Encodation_scheme_name:text\Encodation_scheme_name:text"। टेक्स्ट उदाहरण: @"\ansix12:ANSIX12TEXT\ascii:बैकस्लैश \\ दोगुना होना चाहिए\edifact:EdifactEncodedText" टेक्स्ट में सभी बैकस्लैश (\) डबल होने चाहिए. |

### यह सभी देखें

* नाम स्थान [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->