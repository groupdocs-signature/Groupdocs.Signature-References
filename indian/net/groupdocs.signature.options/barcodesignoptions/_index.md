---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "बारकोड हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 1450
url: /hi/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

बारकोड हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | डिफ़ॉल्ट मानों के साथ BarcodeSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | टेक्स्ट के साथ BarcodeSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | टेक्स्ट के साथ BarcodeSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | सभी डॉक्यूमेंट पेजों पर सिग्नेचर लगाएँ। |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | अतिरिक्त सिग्नेचर रूप। |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | हस्ताक्षर पृष्ठभूमि सेटिंग्स प्राप्त करता है या सेट करता है। |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | बॉर्डर सेटिंग्स निर्दिष्ट करें |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | परिणामस्वरूप Barcode छवि में टेक्स्ट की संरेखण प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान None है। |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | सिग्नेचर विकल्पों का डॉक्यूमेंट टाइप प्राप्त करें या सेट करें [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Barcode प्रकार प्राप्त करता है या सेट करता है। |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | सिग्नेचर एक्सटेंशन। |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | हस्ताक्षर का फ़ॉन्ट प्राप्त करता है या सेट करता है। |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Barcode बारों का Fore रंग प्राप्त करता है या सेट करता है। इस गुण का उपयोग करने से सत्यापन में समस्याएँ हो सकती हैं। सावधानीपूर्वक उपयोग करें। |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | टेक्स्ट फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है जिसमें टेक्स्ट हस्ताक्षर डाला जाता है। यह गुण केवल SignatureImplementation = TextToFormField के साथ उपयोग किया जा सकता है। |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | टेक्स्ट हस्ताक्षर डालने के लिए फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है या सेट करता है। यह गुण केवल SignatureImplementation = TextToFormField के साथ उपयोग किया जा सकता है। डिफ़ॉल्ट मान AllTextTypes है। |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | क्रिप्टोग्राफिक ऑपरेशनों के लिए उपयोग किए जाने वाले हैश एल्गोरिदम को प्राप्त करता है या सेट करता है। यह केवल PDF फ़ाइलों में डिजिटल सिग्नेचर के लिए समर्थित है। |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की ऊँचाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में ([`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType गुण देखें)। |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | डॉक्यूमेंट पेज पर सिग्नेचर का क्षैतिज संरेखण। |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Barcode तत्वों और परिणाम छवि की सीमाओं के बीच अंतराल प्राप्त करता है या सेट करता है। |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाएँ X स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर देखें [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType प्रॉपर्टी) में। (यदि क्षैतिज संरेखण निर्दिष्ट नहीं है तो काम करता है)। |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | बाएँ और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | हस्ताक्षर और दस्तावेज़ किनारों के बीच का अंतराल प्राप्त करता है या सेट करता है। (केवल तब काम करता है जब क्षैतिज या लंबवत संरेखण निर्दिष्ट हो)। |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) प्राप्त करता है या सेट करता है। |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | मूल एट्रिब्यूट को प्राप्त करता है या सेट करता है। यदि इसे सेट किया जाता है तो दस्तावेज़-विशिष्ट हस्ताक्षर उपयोग किए जा सकते हैं। WordProcessing दस्तावेज़ों के लिए मूल टेक्स्ट वॉटरमार्क सामान्य से अलग होता है, उदाहरण के लिए। |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है। न्यूनतम और डिफ़ॉल्ट मान 1 है। |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | हस्ताक्षर किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | हस्ताक्षर की बारकोड छवि सामग्री प्राप्त करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है जो दस्तावेज़ पृष्ठ पर रखी गई थी। यदि यह फ़्लैग true सेट किया जाता है, तो बारकोड हस्ताक्षर छवि सामग्री आवश्यक फ़ॉर्मेट [`ReturnContentType`](./returncontenttype) द्वारा कच्चा इमेज डेटा रखेगी। डिफ़ॉल्ट रूप से यह विकल्प निष्क्रिय है। |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | जब ReturnContent प्रॉपर्टी सक्षम हो तो बारकोड हस्ताक्षर की लौटाई गई छवि सामग्री का फ़ाइल प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट रूप से यह Null पर सेट होता है। इसका अर्थ है कि बारकोड छवि सामग्री मूल फ़ॉर्मेट में लौटाई जाएगी। यह छवि फ़ॉर्मेट [`Format`](../../groupdocs.signature.domain/barcodesignature/format) पर निर्दिष्ट है। संभावित समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया फ़ॉर्मेट समर्थित नहीं है तो बारकोड छवि सामग्री .png फ़ॉर्मेट में लौटाई जाएगी। |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)। |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | परिभाषित करता है कि आकार दस्तावेज़ लेआउट में कहाँ प्रस्तुत किया जाना चाहिए। केवल Word दस्तावेज़ों के लिए उपलब्ध। |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | टेक्स्ट रखने के लिए आकार के प्रकार को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल SignatureImplementation = TextStamp के साथ उपयोग की जा सकती है। डिफ़ॉल्ट मान Rectangle है। |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | हस्ताक्षर की अनूठी ID को प्राप्त करता है या सेट करता है। इसे हस्ताक्षर सत्यापन विकल्पों में उपयोग किया जा सकता है। यह प्रॉपर्टी केवल Pdf दस्तावेज़ों के लिए समर्थित है। |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | टेक्स्ट हस्ताक्षर कार्यान्वयन के प्रकार को प्राप्त करता है या सेट करता है। |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | हस्ताक्षर प्रकार प्राप्त करें [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Width और Height गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | डॉक्यूमेंट पेज पर स्ट्रेच मोड। |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | हस्ताक्षर के टेक्स्ट को प्राप्त करता है या सेट करता है। |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | हस्ताक्षर के भीतर टेक्स्ट का क्षैतिज संरेखण। यह सुविधा केवल Image और Annotation हस्ताक्षर कार्यान्वयनों के लिए समर्थित है (देखें [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation प्रॉपर्टी)। |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | हस्ताक्षर के भीतर टेक्स्ट का लंबवत संरेखण। यह सुविधा केवल Image हस्ताक्षर कार्यान्वयन के लिए समर्थित है (देखें [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation प्रॉपर्टी)। |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में देखें [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType प्रॉपर्टी। (यदि लंबवत संरेखण निर्दिष्ट नहीं है तो काम करता है)। |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | हस्ताक्षर की पारदर्शिता प्राप्त करता है या सेट करता है (मान 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक)। डिफ़ॉल्ट मान 0 (अपारदर्शी) है। |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण। |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में देखें [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType प्रॉपर्टी। |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | पाठ हस्ताक्षर की Z-क्रम स्थिति प्राप्त करता है या सेट करता है। ओवरलैपिंग हस्ताक्षरों के प्रदर्शित क्रम को निर्धारित करता है। |

### टिप्पणियाँ

**Learn more**

* Basic usage of creating Barcode electronic signature by GroupDocs.Signature: [How to eSign document with Barcode signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Barcode signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### संबंधित देखें

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
