---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "इमेज हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 1670
url: /hi/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

इमेज हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | डिफ़ॉल्ट मानों के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | इमेज स्ट्रीम के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | इमेज फ़ाइल के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | सभी डॉक्यूमेंट पेजों पर सिग्नेचर लगाएँ। |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | अतिरिक्त सिग्नेचर रूप। |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | बॉर्डर सेटिंग्स निर्दिष्ट करें |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | सिग्नेचर विकल्पों का डॉक्यूमेंट टाइप प्राप्त करें या सेट करें [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | सिग्नेचर एक्सटेंशन। |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | क्रिप्टोग्राफिक ऑपरेशनों के लिए उपयोग किए जाने वाले हैश एल्गोरिदम को प्राप्त करता है या सेट करता है। यह केवल PDF फ़ाइलों में डिजिटल सिग्नेचर के लिए समर्थित है। |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | डॉक्यूमेंट पेज पर सिग्नेचर की ऊँचाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) में। |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | डॉक्यूमेंट पेज पर सिग्नेचर का क्षैतिज संरेखण। |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | हस्ताक्षर छवि फ़ाइल पथ को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ImageStream निर्दिष्ट नहीं किया गया हो। |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | हस्ताक्षर छवि स्ट्रीम को प्राप्त करता है या सेट करता है। यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा ImageFilePath के बजाय उपयोग की जाती है। |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाएँ X स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) में। (जब क्षैतिज संरेखण निर्दिष्ट नहीं किया गया हो तो काम करता है)। |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | बाएँ और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | हस्ताक्षर और दस्तावेज़ किनारों के बीच का अंतराल प्राप्त करता है या सेट करता है। (केवल तब काम करता है जब क्षैतिज या लंबवत संरेखण निर्दिष्ट हो)। |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) प्राप्त करता है या सेट करता है। |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है। न्यूनतम और डिफ़ॉल्ट मान 1 है। |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | हस्ताक्षर किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | दस्तावेज़ पर छवि रखने के क्षेत्र का आयत। |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)। |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | परिभाषित करता है कि आकार दस्तावेज़ लेआउट में कहाँ प्रस्तुत किया जाना चाहिए। केवल Word दस्तावेज़ों के लिए उपलब्ध। |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | हस्ताक्षर प्रकार प्राप्त करें [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Width और Height गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | डॉक्यूमेंट पेज पर स्ट्रेच मोड। |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) में। (जब लंबवत संरेखण निर्दिष्ट नहीं किया गया हो तो काम करता है)। |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | हस्ताक्षर की पारदर्शिता प्राप्त करता है या सेट करता है (मान 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक)। डिफ़ॉल्ट मान 0 (अपारदर्शी) है। |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण। |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) में। |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | पाठ हस्ताक्षर की Z-क्रम स्थिति प्राप्त करता है या सेट करता है। ओवरलैपिंग हस्ताक्षरों के प्रदर्शित क्रम को निर्धारित करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Base64 से पूर्वनिर्धारित छवि के साथ ImageSignOptions क्लास का नया इंस्टेंस बनाता है। |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | आंतरिक संसाधनों को साफ़ करता है |

### टिप्पणियाँ

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### संबंधित देखें

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
