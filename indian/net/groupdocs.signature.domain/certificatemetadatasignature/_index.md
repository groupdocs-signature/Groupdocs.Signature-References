---
title: CertificateMetadataSignature
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: में प्रमणपत्र मेटडेट हस्तक्षर गुण शमल हैं
type: docs
weight: 70
url: /hi/net/groupdocs.signature.domain/certificatemetadatasignature/
---
## CertificateMetadataSignature class

में प्रमाणपत्र मेटाडेटा हस्ताक्षर गुण शामिल हैं।

```csharp
public sealed class CertificateMetadataSignature : MetadataSignature
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CertificateMetadataSignature](certificatemetadatasignature#constructor)(string) | पूर्वनिर्धारित नाम और खाली मान के साथ प्रमाणपत्र मेटाडेटा हस्ताक्षर बनाता है। |
| [CertificateMetadataSignature](certificatemetadatasignature#constructor_1)(string, object) | पूर्वनिर्धारित मानों के साथ प्रमाणपत्र मेटाडेटा हस्ताक्षर बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें। |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | के कार्यान्वयन को प्राप्त या सेट करता है[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) सांकेतिक शब्दों में बदलना और हस्ताक्षर मूल्य गुणों को डिकोड करने के लिए इंटरफ़ेस। |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | ध्वज प्राप्त करें जो इंगित करता है कि क्या यह हस्ताक्षर दस्तावेज़ से हटा दिया गया था। इस गुण का उपयोग केवल दस्तावेज़ इतिहास लॉग रिकॉर्ड के लिए हटाए गए हस्ताक्षरों की सूची रखने के लिए किया जा रहा है। |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | हस्ताक्षर की ऊंचाई निर्दिष्ट करता है। |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | यह इंगित करने के लिए ध्वज प्राप्त करें या सेट करें कि क्या यह घटक हस्ताक्षर या दस्तावेज़ सामग्री है। इस संपत्ति का उपयोग तत्व को हस्ताक्षर (सत्य) या दस्तावेज़ तत्व (गलत) के रूप में सेट करने के लिए अद्यतन विधि के साथ किया जा रहा है। |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | हस्ताक्षर की बाईं स्थिति निर्दिष्ट करता है। |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | हस्ताक्षर संशोधन दिनांक प्राप्त करें या सेट करें। |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | अद्वितीय मेटाडेटा नाम निर्दिष्ट करता है। |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | निर्दिष्ट करता है कि पृष्ठ हस्ताक्षर पर पाया गया था |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | अद्यतन या हटाने के तरीकों पर दस्तावेज़ में हस्ताक्षर को संशोधित करने के लिए अद्वितीय हस्ताक्षर पहचानकर्ता। यह गुण हस्ताक्षर या खोज विधि को बुलाए जाने के बाद स्वचालित रूप से सेट हो जाएगा। |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | हस्ताक्षर के प्रकार को निर्दिष्ट करता है। |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है। |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | मेटाडेटा मान प्रकार निर्दिष्ट करता है. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | मेटाडेटा ऑब्जेक्ट निर्दिष्ट करता है। |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | हस्ताक्षर की चौड़ाई निर्दिष्ट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/certificatemetadatasignature/clone#clone_1)() | क्लोन मेटाडेटा हस्ताक्षर उदाहरण। |
| override [Clone](../../groupdocs.signature.domain/certificatemetadatasignature/clone#clone)(object) | दिए गए मान के साथ क्लोन सर्टिफिकेट मेटाडेटा सिग्नेचर इंस्टेंस। |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | हस्ताक्षर गुणों की तुलना करने के लिए बराबर विधि को ओवरराइट करता है |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | अक्रमांकन पर मेटाडेटा हस्ताक्षर मूल्य से वस्तु प्राप्त करें। |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | अक्रमांकन पर मेटाडेटा सिग्नेचर टेक्स्ट से ऑब्जेक्ट प्राप्त करें। |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | GetHashCode method को ओवरराइड करता है |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | बूलियन में परिवर्तित होता है। |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | दिनांक समय में परिवर्तित होता है. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | दिनांक समय में परिवर्तित होता है. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | दशमलव में परिवर्तित होता है। |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | दशमलव में परिवर्तित होता है। |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | डबल में परिवर्तित होता है। |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | डबल में परिवर्तित होता है। |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | पूर्णांक में परिवर्तित होता है। |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | फ्लोट में परिवर्तित होता है। |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | फ्लोट में परिवर्तित होता है। |
| override [ToString](../../groupdocs.signature.domain/certificatemetadatasignature/tostring#tostring)() | ओवरराइड ToString () method के साथ स्ट्रिंग में कनवर्ट करता है |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | निर्दिष्ट स्वरूप के साथ स्ट्रिंग में कनवर्ट करता है |
| override [ToString](../../groupdocs.signature.domain/certificatemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | निर्दिष्ट स्वरूप के साथ स्ट्रिंग में कनवर्ट करता है |

### यह सभी देखें

* class [MetadataSignature](../metadatasignature)
* नाम स्थान [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* सभा [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
