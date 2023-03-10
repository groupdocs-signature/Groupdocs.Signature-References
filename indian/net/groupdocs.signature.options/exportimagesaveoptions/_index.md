---
title: ExportImageSaveOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: दस्तवेज़ं क छव में नर्यत करने के लए वकल्प सहेजें.
type: docs
weight: 1360
url: /hi/net/groupdocs.signature.options/exportimagesaveoptions/
---
## ExportImageSaveOptions class

दस्तावेज़ों को छवि में निर्यात करने के लिए विकल्प सहेजें.

```csharp
public class ExportImageSaveOptions : ImageSaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor)() | डिफ़ॉल्ट मानों के साथ ExportAsImageSaveOptions वर्ग का एक नया उदाहरण शुरू करता है। |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor_1)(ImageSaveFileFormat) | निर्दिष्ट फ़ाइल स्वरूप के साथ ExportAsImageSaveOptions वर्ग का एक नया उदाहरण शुरू करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | आउटपुट फ़ाइल पथ में अनुपलब्ध होने पर एक्सटेंशन को स्वचालित रूप से जोड़ने के लिए ध्वज प्राप्त या सेट करता है_ डिफ़ॉल्ट मान गलत है। |
| [Border](../../groupdocs.signature.options/exportimagesaveoptions/border) { get; set; } | इमेज बॉर्डर सेटिंग्स प्राप्त या सेट करता है। डिफ़ॉल्ट रूप से यह मान सेट नहीं है. |
| [ExportAllPages](../../groupdocs.signature.options/exportimagesaveoptions/exportallpages) { get; set; } | प्रत्येक पृष्ठ को निर्यात करने के लिए फ़्लैग करें. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | हस्ताक्षरित दस्तावेज़ का फ़ाइल प्रारूप प्राप्त या सेट करता है। |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | हो जाता है या सेट करता है कि मौजूदा फ़ाइल को नई आउटपुट फ़ाइल के साथ अधिलेखित करना है या नहीं। अन्यथा प्रत्यय के रूप में संख्या के साथ नई फ़ाइल बनाई जाएगी। डिफ़ॉल्ट रूप से यह मान सत्य पर सेट होता है जिसका अर्थ है कि फ़ाइल अधिलेखित हो जाएगी। |
| [PageColumns](../../groupdocs.signature.options/exportimagesaveoptions/pagecolumns) { get; set; } | निर्यात की गई छवियों के लिए स्तंभों की संख्या प्राप्त या सेट करता है। यदि आपको छवियों को एक पंक्ति में रखने की आवश्यकता है तो इस संपत्ति का उपयोग करें। |
| [PageNumber](../../groupdocs.signature.options/exportimagesaveoptions/pagenumber) { get; set; } | निर्यात के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त या सेट करता है। न्यूनतम मान 1. है |
| [PagesSetup](../../groupdocs.signature.options/exportimagesaveoptions/pagessetup) { get; set; } | हस्ताक्षर किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | पासवर्ड सुरक्षा के साथ हस्ताक्षरित दस्तावेज़ को सहेजने के लिए पासवर्ड प्राप्त या सेट करता है। यह संपत्ति छवि दस्तावेज़ों के लिए समर्थित नहीं है। |
| [TiffMultipage](../../groupdocs.signature.options/exportimagesaveoptions/tiffmultipage) { get; set; } | दस्तावेज़ पृष्ठों को टिफ़ छवि में विभिन्न फ़्रेमों पर रखें। |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | हस्ताक्षरित दस्तावेज़ को संरक्षित के रूप में सहेजने के लिए लोडऑप्शन से पासवर्ड का उपयोग करना है या नहीं सेट करता है या सेट करता है। डिफ़ॉल्ट मान सत्य है। यह संपत्ति छवि दस्तावेज़ों के लिए समर्थित नहीं है। |

### यह सभी देखें

* class [ImageSaveOptions](../imagesaveoptions)
* नाम स्थान [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->