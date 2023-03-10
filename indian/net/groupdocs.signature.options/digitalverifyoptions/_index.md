---
title: DigitalVerifyOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: दस्तवेज़ डजटल हस्तक्षर क सत्यपत करने के लए वकल्प रखत है
type: docs
weight: 1350
url: /hi/net/groupdocs.signature.options/digitalverifyoptions/
---
## DigitalVerifyOptions class

दस्तावेज़ डिजिटल हस्ताक्षर को सत्यापित करने के लिए विकल्प रखता है।

```csharp
public class DigitalVerifyOptions : VerifyOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DigitalVerifyOptions](digitalverifyoptions#constructor)() | डिफ़ॉल्ट मानों के साथ डिजिटल सत्यापन विकल्प बनाता है। |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_1)(Stream) | दिए गए प्रमाणपत्र स्ट्रीम के साथ डिजिटल सत्यापन विकल्प बनाता है। |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_2)(string) | दिए गए डिजिटल प्रमाणपत्र फ़ाइल पथ के साथ डिजिटल सत्यापन विकल्प बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने के लिए ध्वजांकित करें। डिफ़ॉल्ट मान सत्य है। |
| [Certificate](../../groupdocs.signature.options/digitalverifyoptions/certificate) { get; } | प्रमाणपत्र फ़ाइलपाथ या स्ट्रीम से X509Certificate2 प्रमाणपत्र प्राप्त करें. |
| [CertificateFilePath](../../groupdocs.signature.options/digitalverifyoptions/certificatefilepath) { get; set; } | डिजिटल प्रमाणपत्र का फ़ाइल पथ. |
| [CertificateStream](../../groupdocs.signature.options/digitalverifyoptions/certificatestream) { get; set; } | डिजिटल प्रमाणपत्र की धारा. |
| [Comments](../../groupdocs.signature.options/digitalverifyoptions/comments) { get; set; } | मान्य करने के लिए डिजिटल हस्ताक्षर की टिप्पणियां. |
| [Contact](../../groupdocs.signature.options/digitalverifyoptions/contact) { get; set; } | हस्ताक्षर संपर्क सत्यापित करने के लिए। |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त एक्सटेंशन। |
| [IssuerName](../../groupdocs.signature.options/digitalverifyoptions/issuername) { get; set; } | प्रमाणपत्र जारी करने वाले का नाम मान्य करने के लिए। वैल्यू केस सेंसिटिव है. अगर यह प्रॉपर्टी सेट है तो सत्यापन जांच करेगा कि सिग्नेचर के जारीकर्ता के नाम में पास वैल्यू शामिल है या इसके बराबर है |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | वैध संपत्ति ध्वज। |
| [Location](../../groupdocs.signature.options/digitalverifyoptions/location) { get; set; } | सत्यापित करने के लिए हस्ताक्षर स्थान। |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | दस्तावेज़ पृष्ठ संख्या सत्यापित की जानी है। यदि संपत्ति सेट नहीं है - दस्तावेज़ के सभी पृष्ठ पहली घटना के लिए सत्यापित किए जाएंगे। न्यूनतम मान 1. है |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | पृष्ठ विकल्प सत्यापित किए जाने वाले पृष्ठों को निर्दिष्ट करने के लिए. |
| [Password](../../groupdocs.signature.options/digitalverifyoptions/password) { get; set; } | यदि आवश्यक हो तो डिजिटल प्रमाणपत्र का पासवर्ड। |
| [Reason](../../groupdocs.signature.options/digitalverifyoptions/reason) { get; set; } | डिजिटल हस्ताक्षर को मान्य करने का कारण. |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalverifyoptions/signdatetimefrom) { get; set; } | सत्यापित करने के लिए डिजिटल हस्ताक्षर की तिथि और समय सीमा। अशक्त मान पर ध्यान नहीं दिया जाएगा. |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalverifyoptions/signdatetimeto) { get; set; } | सत्यापित करने के लिए डिजिटल हस्ताक्षर की तिथि और समय सीमा। अशक्त मान पर ध्यान नहीं दिया जाएगा. |
| [SubjectName](../../groupdocs.signature.options/digitalverifyoptions/subjectname) { get; set; } | प्रमाणित करने के लिए प्रमाणपत्र का विषय विशिष्ट नाम। मान केस संवेदी है. यदि यह गुण सेट किया गया है तो सत्यापन जाँच करेगा कि क्या हस्ताक्षर विषय के नाम में शामिल है या उत्तीर्ण मान के बराबर है |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा डिजिटल इलेक्ट्रॉनिक हस्ताक्षर के सत्यापन का मूल उपयोग। हस्ताक्षर: [ किसी दस्तावेज़ में डिजिटल हस्ताक्षर का ई-सत्यापन कैसे करें](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
* GroupDocs के साथ डिजिटल इलेक्ट्रॉनिक हस्ताक्षर के लिए सत्यापन की सेटिंग का उन्नत उपयोग। हस्ताक्षर: [दस्तावेज़ और अतिरिक्त सेटिंग्स में ई-सत्यापन डिजिटल हस्ताक्षर का उन्नत उपयोग]()

### यह सभी देखें

* class [VerifyOptions](../verifyoptions)
* नाम स्थान [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->