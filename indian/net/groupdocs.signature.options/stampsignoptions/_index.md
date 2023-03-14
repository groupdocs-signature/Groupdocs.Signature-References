---
title: StampSignOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: स्टम्प हस्तक्षर वकल्पं क प्रतनधत्व करत है
type: docs
weight: 1710
url: /hi/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

स्टाम्प हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

```csharp
public class StampSignOptions : ImageSignOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | डिफ़ॉल्ट मानों के साथ StampSignOptions वर्ग का एक नया उदाहरण प्रारंभ करता है। |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | संरेखण विकल्पों के साथ StampSignOptions वर्ग का एक नया उदाहरण प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | सभी दस्तावेज़ पृष्ठों पर हस्ताक्षर करें। यह संपत्ति केवल बहु-फ्रेम छवि प्रारूपों (टिफ) के लिए उपयोग की जा सकती है। |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | अतिरिक्त हस्ताक्षर उपस्थिति। |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | स्टाम्प पृष्ठभूमि प्राप्त या सेट करता है। |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | सिग्नेचर का बैकग्राउंड कलर क्रॉप प्रकार प्राप्त या सेट करता है। |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | सिग्नेचर का बैकग्राउंड इमेज क्रॉप प्रकार प्राप्त या सेट करता है। |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | सीमा सेटिंग निर्दिष्ट करें |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | हस्ताक्षर विकल्पों का दस्तावेज़ प्रकार प्राप्त करें या सेट करें[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | हस्ताक्षर एक्सटेंशन. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | माप मानों में दस्तावेज़ पृष्ठ पर हस्ताक्षर की ऊँचाई (पिक्सेल, प्रतिशत या मिलीमीटर देखें[`MeasureType`](../../groupdocs.signature.domain/measuretype) आकारमाप प्रकार). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण। |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | हस्ताक्षर छवि फ़ाइल पथ प्राप्त या सेट करता है। यह संपत्ति केवल तभी उपयोग की जाती है जब इमेजस्ट्रीम निर्दिष्ट नहीं है। |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | सिग्नेचर इमेज स्ट्रीम को प्राप्त या सेट करता है। |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | आयतों के सेट के रूप में प्रदान की गई आंतरिक रेखाओं की सूची। |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | माप मानों में दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाईं X स्थिति (पिक्सेल, प्रतिशत या मिलीमीटर देखें[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (क्षैतिज संरेखण निर्दिष्ट नहीं होने पर कार्य करता है). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | बाएं और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | साइन और दस्तावेज़ किनारों के बीच स्थान प्राप्त या सेट करता है। (केवल क्षैतिज या लंबवत संरेखण निर्दिष्ट होने पर काम करता है)। |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) प्राप्त या सेट करता है। |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | संकेंद्रित वृत्तों के रूप में प्रदान की गई बाहरी रेखाओं की सूची। |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | हस्ताक्षर करने के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त या सेट करता है। न्यूनतम और डिफ़ॉल्ट मान 1. है |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | हस्ताक्षर किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | छवि को दस्तावेज़ पर रखने के लिए क्षेत्र का आयत। |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | हस्ताक्षर प्रकार प्राप्त करें[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | चौड़ाई और ऊंचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | स्टाम्प प्रकार प्राप्त या सेट करता है। डिफ़ॉल्ट रूप से मान गोल है। |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | दस्तावेज़ पृष्ठ पर खिंचाव मोड। |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | माप मान में दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति (पिक्सेल, प्रतिशत या मिलीमीटर देखें[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (यदि लंबवत संरेखण निर्दिष्ट नहीं है तो कार्य करता है). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | सिग्नेचर ट्रांसपेरेंसी (मान 0.0 (अपारदर्शी) से 1.0 (क्लियर) तक) प्राप्त या सेट करता है। डिफ़ॉल्ट मान 0 (अपारदर्शी) है। |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण। |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | माप मानों में दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई (पिक्सेल, प्रतिशत या मिलीमीटर[`MeasureType`](../../groupdocs.signature.domain/measuretype) आकारमाप प्रकार). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | टेक्स्ट हस्ताक्षर की जेड-ऑर्डर स्थिति प्राप्त या सेट करता है। अतिव्यापी हस्ताक्षरों का प्रदर्शन क्रम निर्धारित करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | आंतरिक संसाधनों को साफ़ करता है |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा स्टाम्प इलेक्ट्रॉनिक हस्ताक्षर बनाने का मूल उपयोग। हस्ताक्षर: [स्टाम्प हस्ताक्षर के साथ दस्तावेज़ पर ई-हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* ग्रुप डॉक्स के साथ स्टाम्प इलेक्ट्रॉनिक हस्ताक्षर की सेटिंग का उन्नत उपयोग। हस्ताक्षर: [स्टाम्प हस्ताक्षर और अतिरिक्त सेटिंग्स के साथ ई-हस्ताक्षर दस्तावेज़ का उन्नत उपयोग](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### यह सभी देखें

* class [ImageSignOptions](../imagesignoptions)
* नाम स्थान [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
