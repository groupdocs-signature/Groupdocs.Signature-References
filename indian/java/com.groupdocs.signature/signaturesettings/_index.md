---
title: "SignatureSettings"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

[Signature](../../com.groupdocs.signature/signature) व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | डिफ़ॉल्ट मानों के साथ डिफ़ॉल्ट SignatureSettings इंस्टेंस बनाता है। |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Logger इम्प्लीमेंटेशन के साथ डिफ़ॉल्ट SignatureSettings इंस्टेंस बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | दस्तावेज़ प्रोसेसिंग के दौरान उपयोग की जाने वाली डिफ़ॉल्ट संस्कृति को प्राप्त करता है या सेट करता है। |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | दस्तावेज़ प्रोसेसिंग के दौरान उपयोग की जाने वाली डिफ़ॉल्ट संस्कृति को प्राप्त करता है या सेट करता है। |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | डॉक्यूमेंट इन्फो परिणाम में हटाए गए सिग्नेचर को शामिल करने वाले फ़्लैग को प्राप्त करता है या सेट करता है। |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | डॉक्यूमेंट इन्फो परिणाम में हटाए गए सिग्नेचर को शामिल करने वाले फ़्लैग को प्राप्त करता है या सेट करता है। |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | जब Update मेथड के पास अपडेट करने के लिए कोई सिग्नेचर नहीं हो तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त करता है या सेट करता है। |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | जब Update मेथड के पास अपडेट करने के लिए कोई सिग्नेचर नहीं हो तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त करता है या सेट करता है। |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | जब Delete मेथड के पास हटाने के लिए कोई प्रभावित सिग्नेचर न हो तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त करता है या सेट करता है। |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | जब Delete मेथड के पास हटाने के लिए कोई प्रभावित सिग्नेचर न हो तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त करता है या सेट करता है। |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | दस्तावेज़ मेटाडेटा सूची में एम्बेडेड मानक दस्तावेज़ मेटाडेटा हस्ताक्षर जैसे लेखक, मालिक, दस्तावेज़ निर्माण तिथि, संशोधित तिथि आदि को शामिल करने के लिए फ़्लैग प्राप्त या सेट करता है। |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | दस्तावेज़ मेटाडेटा सूची में एम्बेडेड मानक दस्तावेज़ मेटाडेटा हस्ताक्षर जैसे लेखक, मालिक, दस्तावेज़ निर्माण तिथि, संशोधित तिथि आदि को शामिल करने के लिए फ़्लैग प्राप्त या सेट करता है। |
|
|  | [getLogger()](#getLogger--) | लॉगिंग (त्रुटियाँ, चेतावनियाँ, ट्रेस) के लिए उपयोग किया गया लॉगर कार्यान्वयन। |
|
|  | [getLogLevel()](#getLogLevel--) | संदेशों को सीमित करने के लिए लॉगिंग स्तर (सभी, ट्रेस, चेतावनियाँ, त्रुटियाँ)। |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | संदेशों को सीमित करने के लिए लॉगिंग स्तर (सभी, ट्रेस, चेतावनियाँ, त्रुटियाँ)। |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


डिफ़ॉल्ट मानों के साथ डिफ़ॉल्ट SignatureSettings इंस्टेंस बनाता है।


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Logger इम्प्लीमेंटेशन के साथ डिफ़ॉल्ट SignatureSettings इंस्टेंस बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


दस्तावेज़ प्रसंस्करण के दौरान उपयोग किए जाने वाले डिफ़ॉल्ट संस्कृति को प्राप्त या सेट करता है। डिफ़ॉल्ट मान "en-US" है।


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


दस्तावेज़ प्रसंस्करण के दौरान उपयोग किए जाने वाले डिफ़ॉल्ट संस्कृति को प्राप्त या सेट करता है। डिफ़ॉल्ट मान "en-US" है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


डॉक्यूमेंट इन्फो परिणाम में हटाए गए सिग्नेचर को शामिल करने वाले फ़्लैग को प्राप्त करता है या सेट करता है।
प्रत्येक Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) में Deleted फ़्लैग है
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) यह पता लगाने के लिए कि इसे हटाया गया था या नहीं।


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


डॉक्यूमेंट इन्फो परिणाम में हटाए गए सिग्नेचर को शामिल करने वाले फ़्लैग को प्राप्त करता है या सेट करता है।
प्रत्येक Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) में Deleted फ़्लैग है
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) यह पता लगाने के लिए कि इसे हटाया गया था या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


जब Update मेथड के पास अपडेट करने के लिए कोई सिग्नेचर नहीं हो तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त करता है या सेट करता है।
यदि यह फ़्लैग true (डिफ़ॉल्ट रूप से) पर सेट किया गया है, तो दस्तावेज़ संबंधित इतिहास प्रक्रिया लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाएगा, भले ही Update मेथड में अपडेट करने के लिए कोई हस्ताक्षर न हो।
जब यह फ़्लैट false पर सेट किया जाता है, तो स्रोत दस्तावेज़ बिल्कुल भी संशोधित नहीं होगा।


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


जब Update मेथड के पास अपडेट करने के लिए कोई सिग्नेचर नहीं हो तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त करता है या सेट करता है।
यदि यह फ़्लैग true (डिफ़ॉल्ट रूप से) पर सेट किया गया है, तो दस्तावेज़ संबंधित इतिहास प्रक्रिया लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाएगा, भले ही Update मेथड में अपडेट करने के लिए कोई हस्ताक्षर न हो।
जब यह फ़्लैट false पर सेट किया जाता है, तो स्रोत दस्तावेज़ बिल्कुल भी संशोधित नहीं होगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


जब Delete मेथड के पास हटाने के लिए कोई प्रभावित सिग्नेचर न हो तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त करता है या सेट करता है।
यदि यह फ़्लैग true (डिफ़ॉल्ट रूप से) पर सेट किया गया है, तो दस्तावेज़ संबंधित इतिहास प्रक्रिया लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाएगा, भले ही Delete मेथड में हटाने के लिए कोई हस्ताक्षर न हो।
जब यह फ़्लैट false पर सेट किया जाता है, तो स्रोत दस्तावेज़ बिल्कुल भी संशोधित नहीं होगा।


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


जब Delete मेथड के पास हटाने के लिए कोई प्रभावित सिग्नेचर न हो तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त करता है या सेट करता है।
यदि यह फ़्लैग true (डिफ़ॉल्ट रूप से) पर सेट किया गया है, तो दस्तावेज़ संबंधित इतिहास प्रक्रिया लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाएगा, भले ही Delete मेथड में हटाने के लिए कोई हस्ताक्षर न हो।
जब यह फ़्लैट false पर सेट किया जाता है, तो स्रोत दस्तावेज़ बिल्कुल भी संशोधित नहीं होगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


दस्तावेज़ मेटाडेटा सूची में एम्बेडेड मानक दस्तावेज़ मेटाडेटा हस्ताक्षर जैसे लेखक, मालिक, दस्तावेज़ निर्माण तिथि, संशोधित तिथि आदि को शामिल करने के लिए फ़्लैग प्राप्त या सेट करता है।
यदि यह फ़्लैग false (डिफ़ॉल्ट रूप से) पर सेट किया गया है, तो GetDocumentInfo इन मेटाडेटा हस्ताक्षरों को शामिल नहीं करेगा।
जब यह फ़्लैग true पर सेट किया जाता है, तो दस्तावेज़ जानकारी इन मानक मेटाडेटा हस्ताक्षरों को शामिल करेगी।


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


दस्तावेज़ मेटाडेटा सूची में एम्बेडेड मानक दस्तावेज़ मेटाडेटा हस्ताक्षर जैसे लेखक, मालिक, दस्तावेज़ निर्माण तिथि, संशोधित तिथि आदि को शामिल करने के लिए फ़्लैग प्राप्त या सेट करता है।
यदि यह फ़्लैग false (डिफ़ॉल्ट रूप से) पर सेट किया गया है, तो GetDocumentInfo इन मेटाडेटा हस्ताक्षरों को शामिल नहीं करेगा।
जब यह फ़्लैग true पर सेट किया जाता है, तो दस्तावेज़ जानकारी इन मानक मेटाडेटा हस्ताक्षरों को शामिल करेगी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


लॉगिंग (त्रुटियाँ, चेतावनियाँ, ट्रेस) के लिए उपयोग किया गया लॉगर कार्यान्वयन। [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


संदेशों को सीमित करने के लिए लॉगिंग स्तर (सभी, ट्रेस, चेतावनियाँ, त्रुटियाँ)।
LogLevel
.
डिफ़ॉल्ट रूप से All स्तर प्रकार सेट किया गया है।


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


संदेशों को सीमित करने के लिए लॉगिंग स्तर (सभी, ट्रेस, चेतावनियाँ, त्रुटियाँ)।
LogLevel
.
डिफ़ॉल्ट रूप से All स्तर प्रकार सेट किया गया है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

