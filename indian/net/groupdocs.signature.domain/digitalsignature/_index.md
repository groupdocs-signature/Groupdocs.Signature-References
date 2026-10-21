---
title: "DigitalSignature"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "डिजिटल सिग्नेचर प्रॉपर्टीज़ शामिल करता है।"
type: docs
weight: 150
url: /hi/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

डिजिटल सिग्नेचर प्रॉपर्टीज़ शामिल करता है।

```csharp
public class DigitalSignature : BaseSignature
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | डिफ़ॉल्ट पैरामीटरों के साथ Digital signature को प्रारंभ करें। |
| [DigitalSignature](digitalsignature#constructor_4)(string) | ज्ञात SignatureId के साथ Digital signature को प्रारंभ करें। |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | निर्दिष्ट प्रमाणपत्र के साथ Digital signature बनाएं। |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | निर्दिष्ट X509 स्टोर के आधार पर Digital signature बनाएं। निर्दिष्ट स्टोर से पहला प्रमाणपत्र उपयोग किया जाएगा। |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | निर्दिष्ट X509 स्टोर और प्रमाणपत्र के सूचकांक के आधार पर Digital signature बनाएं। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | X509 प्रमाणपत्र को प्राप्त करता है या सेट करता है। |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | प्रमाणपत्र के कस्टम स्टोर नाम को निर्दिष्ट करता है। |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | प्रमाणपत्र के स्टोर स्थान को निर्दिष्ट करता है। |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | प्रमाणपत्र के स्टोर नाम को निर्दिष्ट करता है। |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | साइनिंग उद्देश्य टिप्पणी को प्राप्त करता है या सेट करता है। |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें। |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | उस फ़्लैग को प्राप्त करें जो दर्शाता है कि यह हस्ताक्षर दस्तावेज़ से हटाया गया था या नहीं। यह प्रॉपर्टी केवल दस्तावेज़ इतिहास लॉग रिकॉर्ड्स के लिए हटाए गए हस्ताक्षरों की सूची रखने हेतु उपयोग की जाती है। |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | हस्ताक्षर की ऊँचाई निर्दिष्ट करता है। |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | फ़्लैग को प्राप्त करें या सेट करें जो दर्शाता है कि यह घटक हस्ताक्षर है या दस्तावेज़ सामग्री। यह प्रॉपर्टी Update मेथड के साथ उपयोग की जाती है तत्व को हस्ताक्षर (true) या दस्तावेज़ तत्व (false) के रूप में सेट करने के लिए। |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | यदि यह डिजिटल सिग्नेचर वैध है और दस्तावेज़ में कोई छेड़छाड़ नहीं हुई है तो true रखता है। |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | हस्ताक्षर की बायीं स्थिति निर्दिष्ट करता है। |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | हस्ताक्षर संशोधन तिथि प्राप्त करें या सेट करें। |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | वह पृष्ठ निर्दिष्ट करता है जिस पर हस्ताक्षर पाया गया था। |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | हस्ताक्षर को दस्तावेज़ में Update या Delete मेथड्स के माध्यम से संशोधित करने के लिए अद्वितीय हस्ताक्षर पहचानकर्ता। यह प्रॉपर्टी Sign या Search मेथड कॉल होने के बाद स्वचालित रूप से सेट हो जाएगी। यदि यह प्रॉपर्टी पहले सहेजी गई थी तो इसे हस्ताक्षर को नियंत्रित करने के लिए मैन्युअल रूप से सेट किया जा सकता है। |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | हस्ताक्षर के प्रकार को निर्दिष्ट करता है। |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | दस्तावेज़ पर साइन किए जाने का समय प्राप्त करता है या सेट करता है। |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | प्रमाणपत्र का थंबप्रिंट प्राप्त करता है। |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है। |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | हस्ताक्षर की चौड़ाई निर्दिष्ट करता है। |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES प्रकार [`XAdESType`](./xadestype). डिफ़ॉल्ट मान None है (XAdES बंद है). वर्तमान में XAdES हस्ताक्षर प्रकार केवल Spreadsheet दस्तावेज़ों के लिए समर्थित है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | Barcode Signature इंस्टेंस को क्लोन करें। |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | GetHashCode मेथड को ओवरराइड करता है |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | सभी सिस्टम X509 प्रमाणपत्र स्टोर्स से Digital signatures लोड करें। |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | एक प्रमाणपत्र संग्रह से Digital signatures लोड करें। |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | एक प्रमाणपत्र संग्रह से Digital signatures लोड करें। |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | विशिष्ट स्थान पर स्थित डिजिटल प्रमाणपत्र संग्रह से Digital signatures लोड करें। |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | विशिष्ट स्थान पर स्थित डिजिटल प्रमाणपत्र संग्रह से Digital signatures लोड करें। |

### संबंधित देखें

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
