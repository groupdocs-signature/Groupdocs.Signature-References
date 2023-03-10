---
title: FileType
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: फ़इल प्रकर क प्रतनधत्व करत है
type: docs
weight: 450
url: /hi/net/groupdocs.signature.domain/filetype/
---
## FileType class

फ़ाइल प्रकार का प्रतिनिधित्व करता है।

```csharp
public sealed class FileType : IEquatable<FileType>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | फ़ाइल नाम प्रत्यय (अवधि "." सहित) उदाहरण के लिए ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | फ़ाइल प्रकार नाम जैसे "माइक्रोसॉफ्ट वर्ड दस्तावेज़"। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | फ़ाइल प्रकार के लिए मानचित्र फ़ाइल एक्सटेंशन. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | निर्धारित करता है कि क्या वर्तमान[`FileType`](../filetype)निर्दिष्ट के समान है[`FileType`](../filetype) वस्तु. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | निर्धारित करता है कि क्या वर्तमान[`FileType`](../filetype) निर्दिष्ट वस्तु के समान है। |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | वर्तमान के लिए हैश कोड लौटाता है[`FileType`](../filetype) वस्तु. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | एक स्ट्रिंग लौटाता है जो वर्तमान वस्तु का प्रतिनिधित्व करता है। |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | समर्थित फ़ाइल प्रकारों को पुनः प्राप्त करता है |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | निर्धारित करता है कि क्या दो[`FileType`](../filetype) वस्तुएं समान हैं। |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | निर्धारित करता है कि क्या दो[`FileType`](../filetype) वस्तुएं समान नहीं हैं। |

## खेत

| नाम | विवरण |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | बिटमैप छवि फ़ाइल (.bmp) का उपयोग बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए किया जाता है। ये छवियां ग्राफ़िक्स एडॉप्टर से स्वतंत्र हैं और इन्हें डिवाइस स्वतंत्र बिटमैप (DIB) फ़ाइल स्वरूप भी कहा जाता है. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw वेक्टर ग्राफ़िक आरेखण (.cdr) एक वेक्टर आरेखण छवि फ़ाइल है जो मूल रूप से CorelDRAW के साथ एन्कोडेड और संपीड़ित डिजिटल छवि संग्रहीत करने के लिए बनाई गई है। इस तरह की ड्राइंग फ़ाइल में छवि सामग्री के वेक्टर प्रतिनिधित्व के लिए पाठ, रेखाएँ, आकृतियाँ, चित्र, रंग और प्रभाव होते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | कंप्यूटर ग्राफ़िक्स मेटाफ़ाइल (.cgm) वेक्टर ग्राफ़िक्स (2D), रास्टर ग्राफ़िक्स और टेक्स्ट के भंडारण और आदान-प्रदान के लिए एक मुफ़्त, प्लेटफ़ॉर्म-स्वतंत्र, अंतर्राष्ट्रीय मानक मेटाफ़ाइल फ़ॉर्मेट है। सीजीएम वस्तु-उन्मुख दृष्टिकोण और छवि उत्पादन के लिए कई कार्य प्रावधानों का उपयोग करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW मेटाफाइल एक्सचेंज इमेज फाइल (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | अल्पविराम से अलग की गई मान फ़ाइल (.csv) सादे पाठ फ़ाइलों का प्रतिनिधित्व करती है जिनमें अल्पविराम से अलग किए गए मानों के साथ डेटा के रिकॉर्ड होते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | डीआईसीओएम छवि (.डीसीएम) डिजिटल छवि का प्रतिनिधित्व करती है जो रोगियों की चिकित्सा जानकारी जैसे एमआरआई, सीटी स्कैन और अल्ट्रासाउंड छवियों को संग्रहीत करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu छवि (.djvu) स्कैन किए गए दस्तावेज़ों और पुस्तकों के लिए एक ग्राफ़िक्स फ़ाइल स्वरूप है, विशेष रूप से उनमें जिनमें टेक्स्ट, आरेखण, छवियों और फ़ोटोग्राफ़ का संयोजन होता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word दस्तावेज़ (.doc) Microsoft Word या अन्य शब्द संसाधन दस्तावेज़ों द्वारा बाइनरी फ़ाइल स्वरूप में उत्पन्न दस्तावेज़ों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML मैक्रो-सक्षम दस्तावेज़ (.docm) एक Microsoft Word 2007 या उच्च उत्पन्न दस्तावेज़ है जिसमें मैक्रो चलाने की क्षमता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | माइक्रोसॉफ्ट वर्ड ओपन एक्सएमएल दस्तावेज़ (.docx) माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध प्रारूप है। Microsoft Office 2007 की रिलीज़ के साथ 2007 से पेश किया गया, इस नए दस्तावेज़ प्रारूप की संरचना को सादे बाइनरी से XML और बाइनरी फ़ाइलों के संयोजन में बदल दिया गया था। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word दस्तावेज़ टेम्प्लेट (.dot) Microsoft Word द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं जिनमें आगे DOC या DOCX फ़ाइलों को बनाने के लिए पहले से स्वरूपित सेटिंग्स होती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML मैक्रो-सक्षम दस्तावेज़ टेम्पलेट (.dotm) Microsoft Word 2007 या उच्चतर के साथ बनाई गई टेम्पलेट फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | वर्ड ओपन एक्सएमएल डॉक्यूमेंट टेम्प्लेट (.dotx) माइक्रोसॉफ्ट वर्ड द्वारा बनाई गई टेम्प्लेट फाइलें हैं, जिनमें आगे की DOCX फाइलों के निर्माण के लिए पूर्व-स्वरूपित सेटिंग्स हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | एन्हांस्ड विंडोज मेटाफाइल (.emf) ग्राफिकल इमेज डिवाइस को स्वतंत्र रूप से दर्शाता है। ईएमएफ की मेटा-फाइलों में कालानुक्रमिक क्रम में चर-लंबाई के रिकॉर्ड शामिल होते हैं जो किसी भी आउटपुट डिवाइस पर पार्सिंग के बाद संग्रहीत छवि को प्रस्तुत कर सकते हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | एनकैप्सुलेटेड पोस्टस्क्रिप्ट फ़ाइल (.eps) एक एनकैप्सुलेटेड पोस्टस्क्रिप्ट भाषा प्रोग्राम का वर्णन करता है जो एक पृष्ठ के प्रकटन का वर्णन करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | ग्राफ़िकल इंटरचेंज फ़ॉर्मेट फ़ाइल (.gif) एक प्रकार की अत्यधिक संकुचित छवि है। प्रत्येक छवि के लिए जीआईएफ आमतौर पर प्रति पिक्सेल 8 बिट तक की अनुमति देता है और छवि में अधिकतम 256 रंगों की अनुमति है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG छवि (.jpeg) एक प्रकार का छवि प्रारूप है जिसे हानिकारक संपीड़न की विधि का उपयोग करके सहेजा जाता है। संपीड़न के परिणाम के रूप में आउटपुट छवि, भंडारण आकार और छवि गुणवत्ता के बीच एक समझौता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG छवि (.jpg) एक प्रकार का छवि प्रारूप है जिसे हानिकारक संपीड़न की विधि का उपयोग करके सहेजा जाता है। संपीड़न के परिणाम के रूप में आउटपुट छवि, भंडारण आकार और छवि गुणवत्ता के बीच एक समझौता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument ग्राफ़िक फ़ाइल (.odg) का उपयोग Apache OpenOffice के ड्रा एप्लिकेशन द्वारा आरेखण तत्वों को सदिश छवि के रूप में संग्रहीत करने के लिए किया जाता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument प्रस्तुतिकरण (.odp) OASISOpen मानक में OpenOffice.org द्वारा प्रयुक्त प्रस्तुति फ़ाइल स्वरूप का प्रतिनिधित्व करता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument स्प्रेडशीट (.ods) OpenDocument स्प्रेडशीट दस्तावेज़ स्वरूप के लिए है जो उपयोगकर्ता द्वारा संपादन योग्य हैं। डेटा को ODF फ़ाइल में पंक्तियों और स्तंभों में संग्रहीत किया जाता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument टेक्स्ट डॉक्यूमेंट (.odt) एक प्रकार के दस्तावेज़ हैं जो वर्ड प्रोसेसिंग एप्लिकेशन के साथ बनाए जाते हैं जो OpenDocument टेक्स्ट फ़ाइल स्वरूप पर आधारित होते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument प्रस्तुति टेम्पलेट (.otp) OASIS OpenDocument मानक प्रारूप में एप्लिकेशन द्वारा बनाई गई प्रस्तुति टेम्पलेट फ़ाइलों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument स्प्रेडशीट टेम्पलेट (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument दस्तावेज़ टेम्पलेट (.ott) OASIS के OpenDocument मानक प्रारूप के अनुपालन में अनुप्रयोगों द्वारा उत्पन्न टेम्पलेट दस्तावेज़ों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | प्रिंटर कमांड लैंग्वेज डॉक्यूमेंट (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | पोर्टेबल दस्तावेज़ स्वरूप फ़ाइल (.pdf) 1990 के दशक में Adobe द्वारा बनाया गया एक प्रकार का दस्तावेज़ है। इस फ़ाइल प्रारूप का उद्देश्य दस्तावेजों और अन्य संदर्भ सामग्री के प्रतिनिधित्व के लिए एक ऐसे प्रारूप में एक मानक पेश करना था जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और साथ ही ऑपरेटिंग सिस्टम से स्वतंत्र हो। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | स्केलेबल वेक्टर ग्राफ़िक्स फ़ाइल (.svg) एक स्केलर वेक्टर ग्राफ़िक्स फ़ाइल है जो छवि के स्वरूप का वर्णन करने के लिए XML आधारित टेक्स्ट फ़ॉर्मेट का उपयोग करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | पोर्टेबल नेटवर्क ग्राफ़िक (.png) एक प्रकार का रेखापुंज छवि फ़ाइल प्रारूप है जो दोषरहित संपीड़न का उपयोग करता है। यह फ़ाइल प्रारूप ग्राफ़िक्स इंटरचेंज फ़ॉर्मेट (GIF) के प्रतिस्थापन के रूप में बनाया गया था और इसकी कोई कॉपीराइट सीमाएँ नहीं हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint टेम्पलेट (.pot) PowerPoint 97-2003 संस्करणों द्वारा बनाई गई Microsoft PowerPoint टेम्पलेट फ़ाइलों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint ओपन XML मैक्रो-सक्षम प्रस्तुति टेम्पलेट (.potm) मैक्रोज़ के समर्थन के साथ Microsoft PowerPoint टेम्पलेट फ़ाइलें हैं। POTM फाइलें PowerPoint 2007 या इसके बाद के संस्करण के साथ बनाई गई हैं और इसमें डिफ़ॉल्ट सेटिंग्स हैं जिनका उपयोग आगे की प्रस्तुति फ़ाइलों को बनाने के लिए किया जा सकता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint ओपन XML प्रस्तुति टेम्पलेट (.potx) Microsoft PowerPoint टेम्पलेट प्रस्तुतियों का प्रतिनिधित्व करता है जो Microsoft PowerPoint 2007 और इसके बाद के संस्करण के साथ बनाई गई हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint स्लाइड शो (.pps) स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint का उपयोग करके बनाया गया है। PPS फ़ाइल पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint ओपन XML मैक्रो-सक्षम स्लाइड (.ppsm) Microsoft PowerPoint 2007 या उच्चतर के साथ बनाए गए मैक्रो-सक्षम स्लाइड शो फ़ाइल स्वरूप का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint ओपन XML स्लाइड शो (.ppsx) फ़ाइलें स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint 2007 और इसके बाद के संस्करण का उपयोग करके बनाई गई हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint प्रस्तुति (.ppt) PowerPoint फ़ाइल का प्रतिनिधित्व करती है जिसमें स्लाइड शो के रूप में प्रदर्शित करने के लिए स्लाइड का संग्रह होता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint ओपन XML मैक्रो-सक्षम प्रस्तुति मैक्रो-सक्षम प्रस्तुति फ़ाइलें हैं जो Microsoft PowerPoint 2007 या उच्चतर संस्करणों के साथ बनाई गई हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint ओपन XML प्रस्तुति (.pptx) लोकप्रिय Microsoft PowerPoint एप्लिकेशन के साथ बनाई गई प्रस्तुति फ़ाइलें हैं। प्रस्तुति फ़ाइल प्रारूप पीपीटी के पिछले संस्करण के विपरीत जो बाइनरी था, पीपीटीएक्स प्रारूप माइक्रोसॉफ्ट पावरपॉइंट ओपन एक्सएमएल प्रस्तुति फ़ाइल प्रारूप पर आधारित है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | पोस्टस्क्रिप्ट फ़ाइल (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop दस्तावेज़ (.psd) ग्राफिक्स डिज़ाइन और विकास के लिए उपयोग किए जाने वाले Adobe Photoshop के मूल फ़ाइल स्वरूप का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | रिच टेक्स्ट फ़ॉर्मेट फ़ाइल (.rtf) अनुप्रयोगों के भीतर उपयोग के लिए स्वरूपित टेक्स्ट और ग्राफ़िक्स को एन्कोड करने की एक विधि का प्रतिनिधित्व करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | स्केलेबल वेक्टर ग्राफ़िक्स फ़ाइल (.svg) एक स्केलर वेक्टर ग्राफ़िक्स फ़ाइल है जो छवि के स्वरूप का वर्णन करने के लिए XML आधारित टेक्स्ट फ़ॉर्मेट का उपयोग करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | टैग की गई छवि फ़ाइल (.tif) रेखापुंज छवियों का प्रतिनिधित्व करती है जो इस फ़ाइल प्रारूप मानक का अनुपालन करने वाले विभिन्न उपकरणों पर उपयोग के लिए हैं। यह कई रंग स्थानों में पित्त, ग्रेस्केल, पैलेट-रंग और पूर्ण-रंग छवि डेटा का वर्णन करने में सक्षम है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | टैग की गई छवि फ़ाइल प्रारूप (.tiff) रास्टर छवियों का प्रतिनिधित्व करता है जो इस फ़ाइल प्रारूप मानक का अनुपालन करने वाले विभिन्न उपकरणों पर उपयोग के लिए हैं। यह कई रंग स्थानों में पित्त, ग्रेस्केल, पैलेट-रंग और पूर्ण-रंग छवि डेटा का वर्णन करने में सक्षम है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | टैब सेपरेटेड वैल्यू फ़ाइल (.tsv) सादे पाठ प्रारूप में टैब से अलग किए गए डेटा का प्रतिनिधित्व करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | सादा पाठ फ़ाइल (.txt) एक पाठ दस्तावेज़ का प्रतिनिधित्व करता है जिसमें पंक्तियों के रूप में सादा पाठ होता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | अज्ञात फ़ाइल प्रकार का प्रतिनिधित्व करता है। |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard फ़ाइल (.vcf) संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल स्वरूप है। लोकप्रिय सूचना विनिमय अनुप्रयोगों के बीच डेटा विनिमय के लिए प्रारूप का व्यापक रूप से उपयोग किया जाता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | वेबपी छवि (.webp) एक आधुनिक रेखापुंज वेब छवि फ़ाइल प्रारूप है जो दोषरहित और हानिपूर्ण संपीड़न पर आधारित है। यह छवि आकार को काफी कम करते हुए समान छवि गुणवत्ता प्रदान करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | विंडोज मेटाफाइल (.wmf) वेक्टर के साथ-साथ बिटमैप-फॉर्मेट इमेज डेटा को स्टोर करने के लिए माइक्रोसॉफ्ट विंडोज मेटाफाइल (WMF) का प्रतिनिधित्व करता है। इस फाइल फॉर्मेट के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | वर्डपरफेक्ट दस्तावेज़ (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | एक्सेल स्प्रेडशीट (.xls) एक्सेल बाइनरी फ़ाइल स्वरूप का प्रतिनिधित्व करता है। ऐसी फ़ाइलें Microsoft Excel के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे OpenOffice Calc या Apple Numbers द्वारा बनाई जा सकती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | एक्सेल बाइनरी स्प्रेडशीट (.xlsb) एक्सेल बाइनरी फाइल फॉर्मेट को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का एक संग्रह है जो एक्सेल वर्कबुक सामग्री को निर्दिष्ट करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | एक्सेल ओपन एक्सएमएल मैक्रो-सक्षम स्प्रेडशीट (.xlsm) एक प्रकार की स्प्रेडशीट फाइल है जो मैक्रोज़ का समर्थन करती है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | माइक्रोसॉफ्ट एक्सेल ओपन एक्सएमएल स्प्रेडशीट (.xlsx) माइक्रोसॉफ्ट एक्सेल दस्तावेज़ों के लिए एक प्रसिद्ध प्रारूप है जिसे माइक्रोसॉफ्ट द्वारा माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज के साथ पेश किया गया था। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | एक्सेल बाइनरी टेम्प्लेट (.xlt) एक्सेल टेम्प्लेट फ़ाइल स्वरूप का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | एक्सेल ऑफिस ओपनएक्सएमएल फाइल टेम्प्लेट (.xltm) एक्सेल टेम्प्लेट फाइल फॉर्मेट का प्रतिनिधित्व करता है। इस फाइल फॉर्मेट के बारे में अधिक जानें[यहाँ](https://wiki.fileformat.com/spreadsheet/xltm) . |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। हस्ताक्षर: [GroupDocs.Signature द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* C#: में समर्थित स्वरूपों की सूची कैसे प्राप्त करें, इसके बारे में अधिक जानकारी[सी # कोड में समर्थित फ़ाइल स्वरूप कैसे प्राप्त करें](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### यह सभी देखें

* नाम स्थान [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
