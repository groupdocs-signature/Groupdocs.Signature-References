---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature for .NET API रेफ़रेंस"
description: "इमेज मेटाडाटा सिग्नेचर प्रॉपर्टीज़ शामिल करता है।"
type: docs
weight: 740
url: /hi/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

इमेज मेटाडाटा सिग्नेचर प्रॉपर्टीज़ शामिल करता है।

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Id और मान के साथ Image Metadata Signature बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें। |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | इंटरफ़ेस की कार्यान्वयन को प्राप्त करता है या सेट करता है [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) को हस्ताक्षर Value गुणों को एन्कोड और डिकोड करने के लिए। |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | उस फ़्लैग को प्राप्त करें जो दर्शाता है कि यह हस्ताक्षर दस्तावेज़ से हटाया गया था या नहीं। यह प्रॉपर्टी केवल दस्तावेज़ इतिहास लॉग रिकॉर्ड्स के लिए हटाए गए हस्ताक्षरों की सूची रखने हेतु उपयोग की जाती है। |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | स्टैंडर्ड Image Metadata सिग्नेचर के विवरण को प्राप्त करने के लिए रीड-ओनली मान। |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | हस्ताक्षर की ऊँचाई निर्दिष्ट करता है। |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Image Metadata हस्ताक्षर का पहचानकर्ता। देखें ImageMetadataSignatures क्लास जिसमें पूर्वनिर्धारित Id मान के साथ मानक Signature शामिल है। |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | फ़्लैग को प्राप्त करें या सेट करें जो दर्शाता है कि यह घटक हस्ताक्षर है या दस्तावेज़ सामग्री। यह प्रॉपर्टी Update मेथड के साथ उपयोग की जाती है तत्व को हस्ताक्षर (true) या दस्तावेज़ तत्व (false) के रूप में सेट करने के लिए। |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | हस्ताक्षर की बायीं स्थिति निर्दिष्ट करता है। |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | हस्ताक्षर संशोधन तिथि प्राप्त करें या सेट करें। |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | अद्वितीय मेटाडाटा नाम निर्दिष्ट करता है। |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | वह पृष्ठ निर्दिष्ट करता है जिस पर हस्ताक्षर पाया गया था। |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | हस्ताक्षर को दस्तावेज़ में Update या Delete मेथड्स के माध्यम से संशोधित करने के लिए अद्वितीय हस्ताक्षर पहचानकर्ता। यह प्रॉपर्टी Sign या Search मेथड कॉल होने के बाद स्वचालित रूप से सेट हो जाएगी। यदि यह प्रॉपर्टी पहले सहेजी गई थी तो इसे हस्ताक्षर को नियंत्रित करने के लिए मैन्युअल रूप से सेट किया जा सकता है। |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | हस्ताक्षर के प्रकार को निर्दिष्ट करता है। |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Metadata मान का आकार प्राप्त करने के लिए केवल-पढ़ने योग्य मान |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है। |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | मेटाडाटा मान प्रकार निर्दिष्ट करता है। |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | मेटाडाटा ऑब्जेक्ट निर्दिष्ट करता है। |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | हस्ताक्षर की चौड़ाई निर्दिष्ट करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | Metadata Signature इंस्टेंस को क्लोन करें। |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | दिए गए मान के साथ Image Metadata Signature इंस्टेंस को क्लोन करें। |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | डिसेरियलाइज़ेशन के बाद Metadata Signature Value से ऑब्जेक्ट प्राप्त करें। |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | डिसेरियलाइज़ेशन के बाद Metadata Signature Text से ऑब्जेक्ट प्राप्त करें। |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | GetHashCode मेथड को ओवरराइड करता है |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | बूलियन में परिवर्तित करता है। |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | DateTime में परिवर्तित करता है। |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | DateTime में परिवर्तित करता है। |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Decimal में परिवर्तित करता है। |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Decimal में परिवर्तित करता है। |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Double में परिवर्तित करता है। |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Double में परिवर्तित करता है। |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | integer में परिवर्तित करता है। |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | long में परिवर्तित करता है। |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | float में परिवर्तित करता है। |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | float में परिवर्तित करता है। |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | String में परिवर्तित करता है, जिसमें ToString() मेथड को ओवरराइड किया गया है |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | String में परिवर्तित करता है, निर्दिष्ट फ़ॉर्मेट के साथ |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | String में परिवर्तित करता है, निर्दिष्ट फ़ॉर्मेट के साथ |

### संबंधित देखें

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
