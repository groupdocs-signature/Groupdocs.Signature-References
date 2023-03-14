---
title: QrCodeSignOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: क्यूआरकड हस्तक्षर वकल्पं क प्रतनधत्व करत है
type: docs
weight: 1630
url: /hi/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

क्यूआर-कोड हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | डिफ़ॉल्ट मानों के साथ QRCodeSignOptions वर्ग का एक नया उदाहरण आरंभ करता है। |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | पाठ के साथ QRCodeSignOptions वर्ग का एक नया उदाहरण आरंभ करता है। |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | पाठ के साथ BarcodeSignOptions वर्ग का एक नया उदाहरण प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | सभी दस्तावेज़ पृष्ठों पर हस्ताक्षर करें. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | अतिरिक्त हस्ताक्षर उपस्थिति। |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | सिग्नेचर बैकग्राउंड सेटिंग्स प्राप्त या सेट करता है। |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | सीमा सेटिंग निर्दिष्ट करें |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | परिणाम क्यूआर-कोड छवि में पाठ के संरेखण को प्राप्त या सेट करता है। डिफ़ॉल्ट मान कोई नहीं है। |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | क्यूआर-कोड सामग्री को क्रमबद्ध करने के लिए कस्टम ऑब्जेक्ट प्राप्त या सेट करता है। |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | के कार्यान्वयन को प्राप्त या सेट करता है[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) क्यूआर-कोड सिग्नेचर टेक्स्ट या डेटा गुणों को एनकोड और डिकोड करने के लिए इंटरफ़ेस। |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | हस्ताक्षर विकल्पों का दस्तावेज़ प्रकार प्राप्त करें या सेट करें[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | क्यूआर-कोड प्रकार प्राप्त या सेट करता है। |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | हस्ताक्षर एक्सटेंशन. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | हस्ताक्षर का फ़ॉन्ट प्राप्त या सेट करता है। |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | QR-कोड बार्स के अग्र रंग को प्राप्त या सेट करता है इस संपत्ति का उपयोग करने से सत्यापन में समस्या हो सकती है। इसे सावधानी से प्रयोग करें. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | टेक्स्ट फॉर्म फील्ड में टेक्स्ट सिग्नेचर डालने के लिए इसका शीर्षक प्राप्त या सेट करता है। |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | टेक्स्ट सिग्नेचर डालने के लिए फॉर्म फील्ड के प्रकार को प्राप्त या सेट करता है। |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | माप मानों में दस्तावेज़ पृष्ठ पर हस्ताक्षर की ऊँचाई (पिक्सेल, प्रतिशत या मिलीमीटर देखें[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType गुण). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण। |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | क्यूआर-कोड तत्वों और परिणाम छवि सीमाओं के बीच स्थान प्राप्त या सेट करता है। |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | माप मानों में दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाईं X स्थिति (पिक्सेल, प्रतिशत या मिलीमीटर देखें[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType गुण . (क्षैतिज संरेखण निर्दिष्ट नहीं होने पर काम करता है) . |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | बाएं और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | क्यूआर-कोड लोगो छवि फ़ाइल नाम प्राप्त या सेट करता है। यह संपत्ति केवल लोगोस्ट्रीम निर्दिष्ट नहीं होने पर उपयोग में है। इस संपत्ति का उपयोग करने से सत्यापन में समस्या हो सकती है। इसे सावधानी से प्रयोग करें. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | क्यूआर-कोड लोगो छवि स्ट्रीम को प्राप्त या सेट करता है। यदि यह गुण निर्दिष्ट किया गया है तो इसका उपयोग लोगोफाइलपाथ के बजाय हमेशा किया जाता है। इस गुण का उपयोग करने से सत्यापन में समस्या हो सकती है। इसे सावधानी से प्रयोग करें. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | साइन और दस्तावेज़ किनारों के बीच स्थान प्राप्त या सेट करता है। (केवल क्षैतिज या लंबवत संरेखण निर्दिष्ट होने पर काम करता है)। |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) प्राप्त या सेट करता है। |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | मूल विशेषता प्राप्त या सेट करता है। यदि यह सेट है तो दस्तावेज़ विशिष्ट हस्ताक्षरों का उपयोग किया जा सकता है। |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | हस्ताक्षर करने के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त या सेट करता है। न्यूनतम और डिफ़ॉल्ट मान 1. है |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | हस्ताक्षर किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | एक हस्ताक्षर की क्यूआर-कोड छवि सामग्री प्राप्त करने के लिए ध्वज प्राप्त या सेट करता है जिसे दस्तावेज़ पृष्ठ पर रखा गया था। यदि यह ध्वज सही है, तो क्यूआर-कोड हस्ताक्षर छवि सामग्री आवश्यक प्रारूप द्वारा अपरिष्कृत छवि डेटा रखेगी[`ReturnContentType`](./returncontenttype) . डिफ़ॉल्ट रूप से यह विकल्प अक्षम है। |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | रिटर्नकंटेंट गुण सक्षम होने पर क्यूआर-कोड हस्ताक्षर की लौटाई गई छवि सामग्री के फ़ाइल प्रकार को निर्दिष्ट करता है। डिफ़ॉल्ट रूप से यह शून्य पर सेट होता है। इसका मतलब क्यूआर-कोड छवि सामग्री को मूल स्वरूप में वापस करना है। यह छवि प्रारूप निर्दिष्ट किया गया है[`Format`](../../groupdocs.signature.domain/qrcodesignature/format) संभावित समर्थित मान हैं: FileType.JPEG, FileType.PNG, FileType.BMP। यदि प्रदान किया गया प्रारूप समर्थित नहीं है, तो .png प्रारूप में क्यूआर-कोड छवि सामग्री लौटा दी जाएगी। |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | टेक्स्ट डालने के लिए आकार का प्रकार प्राप्त या सेट करता है। इस संपत्ति का उपयोग केवल सिग्नेचर इम्प्लीमेंटेशन = टेक्स्टस्टैम्प के साथ किया जा सकता है। |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | हस्ताक्षर की विशिष्ट आईडी प्राप्त या सेट करता है। इसका उपयोग हस्ताक्षर सत्यापन विकल्पों में किया जा सकता है। संपत्ति केवल पीडीएफ दस्तावेजों के लिए समर्थित है। |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | टेक्स्ट हस्ताक्षर कार्यान्वयन के प्रकार को प्राप्त या सेट करता है। |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | हस्ताक्षर प्रकार प्राप्त करें[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | चौड़ाई और ऊंचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | दस्तावेज़ पृष्ठ पर खिंचाव मोड। |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | हस्ताक्षर का पाठ प्राप्त या सेट करता है। |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | एक हस्ताक्षर के अंदर पाठ का क्षैतिज संरेखण। यह सुविधा केवल छवि और एनोटेशन हस्ताक्षर कार्यान्वयन के लिए समर्थित है (देखें[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) हस्ताक्षर कार्यान्वयन गुण). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | सिग्नेचर के अंदर टेक्स्ट का वर्टिकल अलाइनमेंट। यह फीचर केवल इमेज सिग्नेचर कार्यान्वयन के लिए समर्थित है (देखें[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) हस्ताक्षर कार्यान्वयन संपत्ति)। |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | माप मान में दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति (पिक्सेल, प्रतिशत या मिलीमीटर देखें[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType गुण). (यदि लंबवत संरेखण निर्दिष्ट नहीं है तो कार्य करता है). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | सिग्नेचर ट्रांसपेरेंसी (मान 0.0 (अपारदर्शी) से 1.0 (क्लियर) तक) प्राप्त या सेट करता है। डिफ़ॉल्ट मान 0 (अपारदर्शी) है। |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण। |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | माप मानों में दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई (पिक्सेल, प्रतिशत या मिलीमीटर देखें[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType गुण). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | टेक्स्ट हस्ताक्षर की जेड-ऑर्डर स्थिति प्राप्त या सेट करता है। अतिव्यापी हस्ताक्षरों का प्रदर्शन क्रम निर्धारित करता है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा क्यूआर-कोड इलेक्ट्रॉनिक हस्ताक्षर बनाने का मूल उपयोग। हस्ताक्षर: [क्यूआर-कोड हस्ताक्षर के साथ दस्तावेज़ को ई-हस्ताक्षर कैसे करें](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* GroupDocs के साथ क्यूआर-कोड इलेक्ट्रॉनिक हस्ताक्षर की सेटिंग का उन्नत उपयोग। हस्ताक्षर: [क्यूआर-कोड हस्ताक्षर और अतिरिक्त सेटिंग्स के साथ ई-हस्ताक्षर दस्तावेज़ का उन्नत उपयोग](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### यह सभी देखें

* class [TextSignOptions](../textsignoptions)
* नाम स्थान [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
