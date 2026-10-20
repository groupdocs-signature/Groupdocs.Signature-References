---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "सिग्नेचर प्रीव्यू विकल्पों को दर्शाता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

सिग्नेचर प्रीव्यू विकल्पों को दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | PreviewSignatureOptions ऑब्जेक्ट को प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | हस्ताक्षर को अलग करने के लिए अद्वितीय मान। |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | हस्ताक्षर को अलग करने के लिए अद्वितीय मान। |
|
|  | [getSignOptions()](#getSignOptions--) | पूर्वावलोकन उत्पन्न करने के लिए हस्ताक्षर विकल्प। |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | पूर्वावलोकन उत्पन्न करने के लिए हस्ताक्षर विकल्प। |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | पूर्वावलोकन छवियों के स्वरूप को प्राप्त करता है या सेट करता है। |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | पूर्वावलोकन छवियों के स्वरूप को प्राप्त करता है या सेट करता है। |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


PreviewSignatureOptions ऑब्जेक्ट को प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | पूर्वावलोकन उत्पन्न करने के लिए हस्ताक्षर विकल्प। |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | इंटरफ़ेस जो आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने की विधि को परिभाषित करता है। |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


हस्ताक्षर को अलग करने के लिए अद्वितीय मान।
पूर्वावलोकन विकल्पों की पहचान करने के लिए SignatureId का उपयोग करें।


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


हस्ताक्षर को अलग करने के लिए अद्वितीय मान।
पूर्वावलोकन विकल्पों की पहचान करने के लिए SignatureId का उपयोग करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


पूर्वावलोकन उत्पन्न करने के लिए हस्ताक्षर विकल्प।


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


पूर्वावलोकन उत्पन्न करने के लिए हस्ताक्षर विकल्प।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


पूर्वावलोकन छवियों के स्वरूप को प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान PNG है।


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


पूर्वावलोकन छवियों के स्वरूप को प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान PNG है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

