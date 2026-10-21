---
title: "PresentationMetadataSignature"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "प्रेजेंटेशन मेटाडाटा सिग्नेचर प्रॉपर्टीज़ शामिल करता है।"
type: docs
weight: 920
url: /hi/net/groupdocs.signature.domain/presentationmetadatasignature/
---
## PresentationMetadataSignature class

प्रेजेंटेशन मेटाडाटा सिग्नेचर प्रॉपर्टीज़ शामिल करता है।

```csharp
public sealed class PresentationMetadataSignature : MetadataSignature
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [PresentationMetadataSignature](presentationmetadatasignature#constructor)(string) | निर्धारित नाम और खाली मान के साथ Presentation Metadata Signature बनाता है |
| [PresentationMetadataSignature](presentationmetadatasignature#constructor_1)(string, object) | निर्धारित मानों के साथ Presentation Metadata Signature बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें। |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | इंटरफ़ेस की कार्यान्वयन को प्राप्त करता है या सेट करता है [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) को हस्ताक्षर Value गुणों को एन्कोड और डिकोड करने के लिए। |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | उस फ़्लैग को प्राप्त करें जो दर्शाता है कि यह हस्ताक्षर दस्तावेज़ से हटाया गया था या नहीं। यह प्रॉपर्टी केवल दस्तावेज़ इतिहास लॉग रिकॉर्ड्स के लिए हटाए गए हस्ताक्षरों की सूची रखने हेतु उपयोग की जाती है। |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | हस्ताक्षर की ऊँचाई निर्दिष्ट करता है। |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | फ़्लैग को प्राप्त करें या सेट करें जो दर्शाता है कि यह घटक हस्ताक्षर है या दस्तावेज़ सामग्री। यह प्रॉपर्टी Update मेथड के साथ उपयोग की जाती है तत्व को हस्ताक्षर (true) या दस्तावेज़ तत्व (false) के रूप में सेट करने के लिए। |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | हस्ताक्षर की बायीं स्थिति निर्दिष्ट करता है। |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | हस्ताक्षर संशोधन तिथि प्राप्त करें या सेट करें। |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | अद्वितीय मेटाडाटा नाम निर्दिष्ट करता है। |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | वह पृष्ठ निर्दिष्ट करता है जिस पर हस्ताक्षर पाया गया था। |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | हस्ताक्षर को दस्तावेज़ में Update या Delete मेथड्स के माध्यम से संशोधित करने के लिए अद्वितीय हस्ताक्षर पहचानकर्ता। यह प्रॉपर्टी Sign या Search मेथड कॉल होने के बाद स्वचालित रूप से सेट हो जाएगी। यदि यह प्रॉपर्टी पहले सहेजी गई थी तो इसे हस्ताक्षर को नियंत्रित करने के लिए मैन्युअल रूप से सेट किया जा सकता है। |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | हस्ताक्षर के प्रकार को निर्दिष्ट करता है। |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है। |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | मेटाडाटा मान प्रकार निर्दिष्ट करता है। |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | मेटाडाटा ऑब्जेक्ट निर्दिष्ट करता है। |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | हस्ताक्षर की चौड़ाई निर्दिष्ट करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone_1)() | Metadata Signature इंस्टेंस को क्लोन करें। |
| override [Clone](../../groupdocs.signature.domain/presentationmetadatasignature/clone#clone)(object) | दिए गए मान के साथ Slides Metadata Signature इंस्टेंस को क्लोन करें। |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | डिसेरियलाइज़ेशन के बाद Metadata Signature Value से ऑब्जेक्ट प्राप्त करें। |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | डिसेरियलाइज़ेशन के बाद Metadata Signature Text से ऑब्जेक्ट प्राप्त करें। |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | GetHashCode मेथड को ओवरराइड करता है |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | बूलियन में परिवर्तित करता है। |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | DateTime में परिवर्तित करता है। |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | DateTime में परिवर्तित करता है। |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Decimal में परिवर्तित करता है। |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Decimal में परिवर्तित करता है। |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Double में परिवर्तित करता है। |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Double में परिवर्तित करता है। |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | integer में परिवर्तित करता है। |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | float में परिवर्तित करता है। |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | float में परिवर्तित करता है। |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring)() | String में परिवर्तित करता है, जिसमें ToString() मेथड को ओवरराइड किया गया है |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | String में परिवर्तित करता है, निर्दिष्ट फ़ॉर्मेट के साथ |
| override [ToString](../../groupdocs.signature.domain/presentationmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | String में परिवर्तित करता है, निर्दिष्ट फ़ॉर्मेट के साथ |

### संबंधित देखें

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
