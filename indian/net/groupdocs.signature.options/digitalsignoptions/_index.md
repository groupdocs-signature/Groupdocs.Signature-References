---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "डिजिटल हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 1560
url: /hi/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

डिजिटल हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | डिफ़ॉल्ट मानों के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | सर्टिफ़िकेट स्ट्रीम के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | सर्टिफ़िकेट फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | सर्टिफ़िकेट स्ट्रीम और इमेज स्ट्रीम के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | सर्टिफ़िकेट स्ट्रीम और इमेज फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | सर्टिफ़िकेट फ़ाइल और इमेज स्ट्रीम के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | सर्टिफ़िकेट फ़ाइल और इमेज फ़ाइल के साथ DigitalSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | एक फ़्लैग प्राप्त करता है या सेट करता है जो समाप्त वैधता अवधि वाले सर्टिफ़िकेट के साथ साइन करने की अनुमति देता है। डिफ़ॉल्ट मान false है: समाप्त सर्टिफ़िकेट के साथ साइन करने पर [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception) फेंका जाता है, और दस्तावेज़ साइन नहीं होता। |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | एक फ़्लैग प्राप्त करता है या सेट करता है जो अभी शुरू नहीं हुई वैधता अवधि वाले सर्टिफ़िकेट के साथ साइन करने की अनुमति देता है। डिफ़ॉल्ट मान false है: ऐसे सर्टिफ़िकेट के साथ साइन करने पर [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception) फेंका जाता है, और दस्तावेज़ साइन नहीं होता। |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | सभी डॉक्यूमेंट पेजों पर सिग्नेचर लगाएँ। |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | अतिरिक्त सिग्नेचर रूप। |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | बॉर्डर सेटिंग्स निर्दिष्ट करें |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | डिजिटल सर्टिफ़िकेट फ़ाइल पाथ को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब उपयोग होती है जब CertificateStream निर्दिष्ट नहीं किया गया हो। |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | डिजिटल सर्टिफ़िकेट स्ट्रीम को प्राप्त करता है या सेट करता है। यदि यह प्रॉपर्टी निर्दिष्ट है तो यह हमेशा CertificateFilePath के बजाय उपयोग की जाती है। |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | सिग्नेचर संपर्क को प्राप्त करता है या सेट करता है। |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | एक कस्टम हैश साइनिंग फ़ंक्शन प्राप्त करता है या सेट करता है, जिससे उपयोगकर्ता अपनी डिजिटल साइनिंग लॉजिक को लागू कर सकें। यह बाहरी सर्टिफ़िकेट के साथ साइन करने को सक्षम करता है और विभिन्न हैश एल्गोरिदम को सपोर्ट करता है। |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | सिग्नेचर विकल्पों का डॉक्यूमेंट टाइप प्राप्त करें या सेट करें [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | सिग्नेचर एक्सटेंशन। |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | क्रिप्टोग्राफिक ऑपरेशनों के लिए उपयोग किए जाने वाले हैश एल्गोरिदम को प्राप्त करता है या सेट करता है। यह केवल PDF फ़ाइलों में डिजिटल सिग्नेचर के लिए समर्थित है। |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | डॉक्यूमेंट पेज पर सिग्नेचर की ऊँचाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) में। |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | डॉक्यूमेंट पेज पर सिग्नेचर का क्षैतिज संरेखण। |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | हस्ताक्षर छवि फ़ाइल पथ को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ImageStream निर्दिष्ट नहीं किया गया हो। |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | हस्ताक्षर छवि स्ट्रीम को प्राप्त करता है या सेट करता है। यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा ImageFilePath के बजाय उपयोग की जाती है। |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाएँ X स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) में। (जब क्षैतिज संरेखण निर्दिष्ट नहीं किया गया हो तो काम करता है)। |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | हस्ताक्षर स्थान को प्राप्त करता है या सेट करता है। |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | बाएँ और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | हस्ताक्षर और दस्तावेज़ किनारों के बीच का अंतराल प्राप्त करता है या सेट करता है। (केवल तब काम करता है जब क्षैतिज या लंबवत संरेखण निर्दिष्ट हो)। |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) प्राप्त करता है या सेट करता है। |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है। न्यूनतम और डिफ़ॉल्ट मान 1 है। |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | हस्ताक्षर किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | डिजिटल सर्टिफ़िकेट का पासवर्ड प्राप्त करता है या सेट करता है। |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | हस्ताक्षर का कारण प्राप्त करता है या सेट करता है। |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | दस्तावेज़ पर छवि रखने के क्षेत्र का आयत। |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)। |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | परिभाषित करता है कि आकार दस्तावेज़ लेआउट में कहाँ प्रस्तुत किया जाना चाहिए। केवल Word दस्तावेज़ों के लिए उपलब्ध। |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | दस्तावेज़ डिजिटल हस्ताक्षर की गुणधर्मों को प्राप्त करता है या सेट करता है। PDF दस्तावेज़ों पर हस्ताक्षर करने के लिए उन्नत गुणधर्म सेट करना संभव है, इसके लिए [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) की इंस्टेंस का उपयोग किया जाता है। |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | हस्ताक्षर प्रकार प्राप्त करें [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Width और Height गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | डॉक्यूमेंट पेज पर स्ट्रेच मोड। |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) में। (जब लंबवत संरेखण निर्दिष्ट नहीं किया गया हो तो काम करता है)। |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | हस्ताक्षर की पारदर्शिता प्राप्त करता है या सेट करता है (मान 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक)। डिफ़ॉल्ट मान 0 (अपारदर्शी) है। |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | ltv (दीर्घकालिक मान्यकरण) मान्यकरण फ़्लैग को प्राप्त करता है/सेट करता है। |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण। |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | हस्ताक्षर की दृश्यता को प्राप्त करता है या सेट करता है। |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) में। |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES प्रकार [`XAdESType`](./xadestype). डिफ़ॉल्ट मान None है (XAdES बंद है). वर्तमान में XAdES हस्ताक्षर प्रकार केवल Spreadsheet दस्तावेज़ों के लिए समर्थित है। |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | पाठ हस्ताक्षर की Z-क्रम स्थिति प्राप्त करता है या सेट करता है। ओवरलैपिंग हस्ताक्षरों के प्रदर्शित क्रम को निर्धारित करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | आंतरिक संसाधनों को साफ़ करता है |

### टिप्पणियाँ

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### संबंधित देखें

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
