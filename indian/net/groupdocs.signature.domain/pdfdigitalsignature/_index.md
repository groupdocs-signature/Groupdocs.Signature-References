---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "Pdf डिजिटल सिग्नेचर प्रॉपर्टीज़ शामिल करता है।"
type: docs
weight: 840
url: /hi/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

Pdf डिजिटल सिग्नेचर प्रॉपर्टीज़ शामिल करता है।

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | कोई प्रमाणपत्र नहीं होने पर Pdf Digital Signature को प्रारंभ करें। |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | निर्दिष्ट प्रमाणपत्र के साथ Pdf Digital Signature बनाएं। |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | निर्दिष्ट X509 स्टोर के आधार पर Pdf Digital Signature को प्रारंभ करें। निर्दिष्ट स्टोर से पहला प्रमाणपत्र उपयोग किया जाएगा। |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | निर्दिष्ट X509 स्टोर और प्रमाणपत्र के इंडेक्स के आधार पर Pdf Digital Signature बनाएं। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | X509 प्रमाणपत्र को प्राप्त करता है या सेट करता है। |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | प्रमाणपत्र के कस्टम स्टोर नाम को निर्दिष्ट करता है। |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | प्रमाणपत्र के स्टोर स्थान को निर्दिष्ट करता है। |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | प्रमाणपत्र के स्टोर नाम को निर्दिष्ट करता है। |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | साइनिंग उद्देश्य टिप्पणी को प्राप्त करता है या सेट करता है। |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | साइनर द्वारा प्रदान की गई जानकारी जिससे प्राप्तकर्ता साइनर से संपर्क करके सिग्नेचर की पुष्टि कर सके, उदाहरण के लिए फ़ोन नंबर। |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें। |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | उस फ़्लैग को प्राप्त करें जो दर्शाता है कि यह हस्ताक्षर दस्तावेज़ से हटाया गया था या नहीं। यह प्रॉपर्टी केवल दस्तावेज़ इतिहास लॉग रिकॉर्ड्स के लिए हटाए गए हस्ताक्षरों की सूची रखने हेतु उपयोग की जाती है। |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | हस्ताक्षर की ऊँचाई निर्दिष्ट करता है। |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | फ़्लैग को प्राप्त करें या सेट करें जो दर्शाता है कि यह घटक हस्ताक्षर है या दस्तावेज़ सामग्री। यह प्रॉपर्टी Update मेथड के साथ उपयोग की जाती है तत्व को हस्ताक्षर (true) या दस्तावेज़ तत्व (false) के रूप में सेट करने के लिए। |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | यदि यह डिजिटल सिग्नेचर वैध है और दस्तावेज़ में कोई छेड़छाड़ नहीं हुई है तो true रखता है। |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | हस्ताक्षर की बायीं स्थिति निर्दिष्ट करता है। |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | साइनिंग का CPU होस्ट नाम या भौतिक स्थान। |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | हस्ताक्षर संशोधन तिथि प्राप्त करें या सेट करें। |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | वह पृष्ठ निर्दिष्ट करता है जिस पर हस्ताक्षर पाया गया था। |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | साइनिंग का कारण, जैसे (I agreeРІР‚В¦)। |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | सिग्नेचर प्रॉपर्टीज़ को दिखाने/छिपाने के लिए मजबूर करें। यदि ShowProperties true है तो सिग्नेचर फ़ील्ड में पूर्वनिर्धारित रूप दिखावट होती है Digitally signed by {[`ContactInfo`](./contactinfo)} Date: {Date} Reason: {[`Reason`](./reason)} Location: {[`Location`](./location)} ShowProperties डिफ़ॉल्ट रूप से true है। |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | हस्ताक्षर को दस्तावेज़ में Update या Delete मेथड्स के माध्यम से संशोधित करने के लिए अद्वितीय हस्ताक्षर पहचानकर्ता। यह प्रॉपर्टी Sign या Search मेथड कॉल होने के बाद स्वचालित रूप से सेट हो जाएगी। यदि यह प्रॉपर्टी पहले सहेजी गई थी तो इसे हस्ताक्षर को नियंत्रित करने के लिए मैन्युअल रूप से सेट किया जा सकता है। |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | हस्ताक्षर के प्रकार को निर्दिष्ट करता है। |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | दस्तावेज़ पर साइन किए जाने का समय प्राप्त करता है या सेट करता है। |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | प्रमाणपत्र का थंबप्रिंट प्राप्त करता है। |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Pdf डिजिटल सिग्नेचर के लिए टाइम स्टैंप। डिफ़ॉल्ट मान null है। |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है। |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Pdf डिजिटल सिग्नेचर का प्रकार। |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | हस्ताक्षर की चौड़ाई निर्दिष्ट करता है। |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES प्रकार [`XAdESType`](../digitalsignature/xadestype)। डिफ़ॉल्ट मान None (XAdES बंद है)। वर्तमान में XAdES सिग्नेचर प्रकार केवल Spreadsheet दस्तावेज़ों के लिए समर्थित है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Barcode Signature इंस्टेंस को क्लोन करें। |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | GetHashCode मेथड को ओवरराइड करता है |

### संबंधित देखें

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
