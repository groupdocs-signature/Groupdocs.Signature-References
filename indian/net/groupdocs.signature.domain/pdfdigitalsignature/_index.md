---
title: PdfDigitalSignature
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: में पडएफ डजटल हस्तक्षर गुण शमल हैं
type: docs
weight: 660
url: /hi/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

में पीडीएफ डिजिटल हस्ताक्षर गुण शामिल हैं।

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | बिना किसी प्रमाण पत्र के पीडीएफ डिजिटल हस्ताक्षर प्रारंभ करें। |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | निर्दिष्ट प्रमाणपत्र के साथ पीडीएफ डिजिटल हस्ताक्षर बनाएं। |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | निर्दिष्ट X509 स्टोर के आधार पर पीडीएफ डिजिटल हस्ताक्षर प्रारंभ करें। निर्दिष्ट स्टोर से प्रथम प्रमाणपत्र का उपयोग किया जाएगा. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | निर्दिष्ट X509 स्टोर और प्रमाणपत्र के सूचकांक के आधार पर पीडीएफ डिजिटल हस्ताक्षर बनाएं। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | X509 प्रमाणपत्र प्राप्त या सेट करता है। |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | प्रमाणपत्र के स्टोर स्थान को निर्दिष्ट करता है |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | प्रमाणपत्र के स्टोर नाम को निर्दिष्ट करता है। |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | साइनिंग उद्देश्य टिप्पणी प्राप्त या सेट करता है। |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | हस्ताक्षरकर्ता द्वारा प्रदान की गई जानकारी हस्ताक्षरकर्ता से संपर्क करने के लिए प्राप्तकर्ता को सक्षम करने के लिए हस्ताक्षर सत्यापित करने के लिए, उदाहरण के लिए एक फोन नंबर। |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें। |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | ध्वज प्राप्त करें जो इंगित करता है कि क्या यह हस्ताक्षर दस्तावेज़ से हटा दिया गया था। इस गुण का उपयोग केवल दस्तावेज़ इतिहास लॉग रिकॉर्ड के लिए हटाए गए हस्ताक्षरों की सूची रखने के लिए किया जा रहा है। |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | हस्ताक्षर की ऊंचाई निर्दिष्ट करता है। |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | यह इंगित करने के लिए ध्वज प्राप्त करें या सेट करें कि क्या यह घटक हस्ताक्षर या दस्तावेज़ सामग्री है। इस संपत्ति का उपयोग तत्व को हस्ताक्षर (सत्य) या दस्तावेज़ तत्व (गलत) के रूप में सेट करने के लिए अद्यतन विधि के साथ किया जा रहा है। |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | सही रहता है अगर यह डिजिटल हस्ताक्षर वैध है और दस्तावेज़ के साथ छेड़छाड़ नहीं की गई है। |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | हस्ताक्षर की बाईं स्थिति निर्दिष्ट करता है। |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | सीपीयू होस्ट नाम या हस्ताक्षर करने का भौतिक स्थान। |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | हस्ताक्षर संशोधन दिनांक प्राप्त करें या सेट करें। |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | निर्दिष्ट करता है कि पृष्ठ हस्ताक्षर पर पाया गया था |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | हस्ताक्षर करने का कारण, जैसे (मैं सहमतРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | हस्ताक्षर गुणों को दिखाने/छिपाने के लिए बाध्य करें। अगर शोप्रॉपर्टीज सही है, तो सिग्नेचर फील्ड उपस्थिति का पूर्वनिर्धारित प्रारूप है डिजिटल रूप से { द्वारा हस्ताक्षरित[`ContactInfo`](./contactinfo)} दिनांक: {दिनांक} कारण: {[`Reason`](./reason) स्थान: {[`Location`](./location) शोप्रॉपर्टीज डिफ़ॉल्ट रूप से सत्य है। |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | अद्यतन या हटाने के तरीकों पर दस्तावेज़ में हस्ताक्षर को संशोधित करने के लिए अद्वितीय हस्ताक्षर पहचानकर्ता। यह गुण हस्ताक्षर या खोज विधि को बुलाए जाने के बाद स्वचालित रूप से सेट हो जाएगा। |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | हस्ताक्षर के प्रकार को निर्दिष्ट करता है। |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | दस्तावेज़ पर हस्ताक्षर किए जाने का समय प्राप्त या सेट करता है। |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | प्रमाणपत्र का थंबप्रिंट प्राप्त करता है। |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | पीडीएफ़ डिजिटल हस्ताक्षर के लिए टाइम स्टैम्प. डिफ़ॉल्ट मान शून्य है. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है। |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | पीडीएफ डिजिटल हस्ताक्षर का प्रकार। |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | हस्ताक्षर की चौड़ाई निर्दिष्ट करता है। |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES प्रकार[`XAdESType`](../digitalsignature/xadestype) . डिफ़ॉल्ट मान कोई नहीं है (XAdES बंद है). इस समय XAdES हस्ताक्षर प्रकार केवल स्प्रेडशीट दस्तावेज़ों के लिए समर्थित है. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | क्लोन बारकोड सिग्नेचर इंस्टेंस. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | हस्ताक्षर गुणों की तुलना करने के लिए बराबर विधि को ओवरराइट करता है |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | GetHashCode method को ओवरराइड करता है |

### यह सभी देखें

* class [DigitalSignature](../digitalsignature)
* नाम स्थान [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
