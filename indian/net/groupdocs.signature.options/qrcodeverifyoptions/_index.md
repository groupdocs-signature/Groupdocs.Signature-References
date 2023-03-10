---
title: QrCodeVerifyOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: दस्तवेज़ क्यूआरकड हस्तक्षर क सत्यपत करने के लए वकल्प रखत है
type: docs
weight: 1640
url: /hi/net/groupdocs.signature.options/qrcodeverifyoptions/
---
## QrCodeVerifyOptions class

दस्तावेज़ क्यूआर-कोड हस्ताक्षर को सत्यापित करने के लिए विकल्प रखता है।

```csharp
public class QrCodeVerifyOptions : TextVerifyOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor)() | क्यूआर-कोड हस्ताक्षरों के लिए सत्यापन विकल्प QrCodeVerifyOptions बनाता है। |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_1)(string) | सत्यापित करने के लिए क्यूआर-कोड टेक्स्ट के साथ क्यूआर-कोड हस्ताक्षर के लिए सत्यापन विकल्प QrCodeVerifyOptions बनाता है। |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_2)(string, QrCodeType) | पाठ के साथ क्यूआर-कोड हस्ताक्षर के लिए सत्यापन विकल्प QrCodeVerifyOptions बनाता है और सत्यापित करने के लिए क्यूआर-कोड एनकोड प्रकार। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने के लिए ध्वजांकित करें। डिफ़ॉल्ट मान सत्य है। |
| [DataEncryption](../../groupdocs.signature.options/qrcodeverifyoptions/dataencryption) { get; set; } | के कार्यान्वयन को प्राप्त या सेट करता है[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) क्यूआर-कोड सिग्नेचर टेक्स्ट प्रॉपर्टीज को एनकोड और डिकोड करने के लिए इंटरफ़ेस। |
| [EncodeType](../../groupdocs.signature.options/qrcodeverifyoptions/encodetype) { get; set; } | क्यूआर-कोड प्रकार सत्यापन प्राप्त या सेट करता है। यह संपत्ति वैकल्पिक है। |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त एक्सटेंशन। |
| [FormTextFieldTitle](../../groupdocs.signature.options/textverifyoptions/formtextfieldtitle) { get; set; } | इसे सत्यापित करने के लिए फॉर्म फ़ील्ड का शीर्षक प्राप्त या सेट करता है। यदि यह गुण सेट टेक्स्ट केवल टेक्स्ट फॉर्म फ़ील्ड में पाया जाएगा। |
| [FormTextFieldType](../../groupdocs.signature.options/textverifyoptions/formtextfieldtype) { get; set; } | इसे सत्यापित करने के लिए फॉर्म फ़ील्ड के प्रकार को प्राप्त या सेट करता है। यदि यह गुण सेट टेक्स्ट केवल टेक्स्ट फॉर्म फ़ील्ड में पाया जाएगा। |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | वैध संपत्ति ध्वज। |
| [MatchType](../../groupdocs.signature.options/textverifyoptions/matchtype) { get; set; } | पाठ मिलान प्रकार सत्यापन प्राप्त या सेट करता है। |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | दस्तावेज़ पृष्ठ संख्या सत्यापित की जानी है। यदि संपत्ति सेट नहीं है - दस्तावेज़ के सभी पृष्ठ पहली घटना के लिए सत्यापित किए जाएंगे। न्यूनतम मान 1. है |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | पृष्ठ विकल्प सत्यापित किए जाने वाले पृष्ठों को निर्दिष्ट करने के लिए. |
| [SignatureID](../../groupdocs.signature.options/textverifyoptions/signatureid) { get; set; } | टेक्स्ट सिग्नेचर आईडी शून्य से अधिक निर्दिष्ट करें यदि इसे सत्यापित किया जाना चाहिए। यह संपत्ति केवल पीडीएफ़ दस्तावेज़ के लिए समर्थित है |
| [SignatureImplementation](../../groupdocs.signature.options/textverifyoptions/signatureimplementation) { get; set; } | सत्यापित किए जाने वाले हस्ताक्षर का प्रकार। |
| [Text](../../groupdocs.signature.options/textverifyoptions/text) { get; set; } | हस्ताक्षर पाठ निर्दिष्ट करें यदि इसे सत्यापित किया जाना चाहिए। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा क्यूआर-कोड इलेक्ट्रॉनिक हस्ताक्षर के सत्यापन का मूल उपयोग। हस्ताक्षर: [ किसी दस्तावेज़ में क्यूआर-कोड हस्ताक्षरों का ई-सत्यापन कैसे करें](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document)
* GroupDocs के साथ क्यूआर-कोड इलेक्ट्रॉनिक हस्ताक्षर के सत्यापन की सेटिंग का उन्नत उपयोग। हस्ताक्षर: [दस्तावेज़ और अतिरिक्त सेटिंग्स में ई-सत्यापन क्यूआर-कोड हस्ताक्षरों का उन्नत उपयोग](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures)

### यह सभी देखें

* class [TextVerifyOptions](../textverifyoptions)
* नाम स्थान [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->