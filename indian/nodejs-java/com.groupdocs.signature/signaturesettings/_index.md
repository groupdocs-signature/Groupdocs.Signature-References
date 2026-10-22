---
title: "SignatureSettings"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature/signaturesettings/
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
| [SignatureSettings()](#SignatureSettings--) | डिफ़ॉल्ट मानों के साथ डिफ़ॉल्ट SignatureSettings इंस्टेंस बनाता है। |
| [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Logger कार्यान्वयन के साथ डिफ़ॉल्ट SignatureSettings इंस्टेंस बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getDefaultCulture()](#getDefaultCulture--) | दस्तावेज़ प्रसंस्करण के दौरान उपयोग की जाने वाली डिफ़ॉल्ट संस्कृति को प्राप्त या सेट करता है। |
| [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | दस्तावेज़ प्रसंस्करण के दौरान उपयोग की जाने वाली डिफ़ॉल्ट संस्कृति को प्राप्त या सेट करता है। |
| [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | डॉक्यूमेंट इन्फो परिणाम में हटाए गए हस्ताक्षरों को शामिल करने वाले फ़्लैग को प्राप्त या सेट करता है। |
| [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | डॉक्यूमेंट इन्फो परिणाम में हटाए गए हस्ताक्षरों को शामिल करने वाले फ़्लैग को प्राप्त या सेट करता है। |
| [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | जब Update मेथड में अपडेट करने के लिए कोई हस्ताक्षर नहीं होते हैं तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त या सेट करता है। |
| [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | जब Update मेथड में अपडेट करने के लिए कोई हस्ताक्षर नहीं होते हैं तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त या सेट करता है। |
| [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | जब Delete मेथड में हटाने के लिए कोई प्रभावित हस्ताक्षर नहीं होते हैं तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त या सेट करता है। |
| [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | जब Delete मेथड में हटाने के लिए कोई प्रभावित हस्ताक्षर नहीं होते हैं तो स्रोत दस्तावेज़ को पुनः सहेजने के फ़्लैग को प्राप्त या सेट करता है। |
| [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | लेखक, मालिक, दस्तावेज़ निर्माण तिथि, संशोधित तिथि आदि जैसे एम्बेडेड मानक दस्तावेज़ मेटाडेटा हस्ताक्षरों को मेटाडेटा सूची में शामिल करने के फ़्लैग को प्राप्त या सेट करता है। |
| [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | लेखक, मालिक, दस्तावेज़ निर्माण तिथि, संशोधित तिथि आदि जैसे एम्बेडेड मानक दस्तावेज़ मेटाडेटा हस्ताक्षरों को मेटाडेटा सूची में शामिल करने के फ़्लैग को प्राप्त या सेट करता है। |
| [getLogger()](#getLogger--) | लॉगिंग (Errors, Warnings, Traces) के लिए उपयोग किया गया लॉगर कार्यान्वयन। |
| [getLogLevel()](#getLogLevel--) | संदेशों को सीमित करने के लिए लॉगिंग स्तर (All, Traces, Warnings, Errors)। |
| [setLogLevel(int value)](#setLogLevel-int-) | संदेशों को सीमित करने के लिए लॉगिंग स्तर (All, Traces, Warnings, Errors)। |
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


डिफ़ॉल्ट मानों के साथ डिफ़ॉल्ट SignatureSettings इंस्टेंस बनाता है।

### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Logger कार्यान्वयन के साथ डिफ़ॉल्ट SignatureSettings इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


दस्तावेज़ प्रसंस्करण के दौरान उपयोग की जाने वाली डिफ़ॉल्ट संस्कृति को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान "en-US" है।

**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


दस्तावेज़ प्रसंस्करण के दौरान उपयोग की जाने वाली डिफ़ॉल्ट संस्कृति को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान "en-US" है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


डिलीट किए गए हस्ताक्षरों को Document Info परिणाम में शामिल करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। प्रत्येक Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) में Deleted फ़्लैग होता है  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) यह पता लगाने के लिए कि इसे डिलीट किया गया था या नहीं।

**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


डिलीट किए गए हस्ताक्षरों को Document Info परिणाम में शामिल करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। प्रत्येक Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) में Deleted फ़्लैग होता है  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) यह पता लगाने के लिए कि इसे डिलीट किया गया था या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


जब Update मेथड में अपडेट करने के लिए कोई हस्ताक्षर नहीं होते हैं, तो स्रोत दस्तावेज़ को पुनः सहेजने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। यदि यह फ़्लैग true (डिफ़ॉल्ट रूप से) पर सेट है, तो दस्तावेज़ संबंधित इतिहास प्रक्रिया लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाएगा, भले ही Update मेथड में अपडेट करने के लिए कोई हस्ताक्षर न हों। जब यह फ़्लैग false पर सेट किया जाता है, तो स्रोत दस्तावेज़ बिल्कुल नहीं बदलेगा।

**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


जब Update मेथड में अपडेट करने के लिए कोई हस्ताक्षर नहीं होते हैं, तो स्रोत दस्तावेज़ को पुनः सहेजने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। यदि यह फ़्लैग true (डिफ़ॉल्ट रूप से) पर सेट है, तो दस्तावेज़ संबंधित इतिहास प्रक्रिया लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाएगा, भले ही Update मेथड में अपडेट करने के लिए कोई हस्ताक्षर न हों। जब यह फ़्लैग false पर सेट किया जाता है, तो स्रोत दस्तावेज़ बिल्कुल नहीं बदलेगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


जब Delete मेथड में हटाने के लिए कोई प्रभावित हस्ताक्षर नहीं होते हैं, तो स्रोत दस्तावेज़ को पुनः सहेजने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। यदि यह फ़्लैग true (डिफ़ॉल्ट रूप से) पर सेट है, तो दस्तावेज़ संबंधित इतिहास प्रक्रिया लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाएगा, भले ही Delete मेथड में हटाने के लिए कोई हस्ताक्षर न हों। जब यह फ़्लैग false पर सेट किया जाता है, तो स्रोत दस्तावेज़ बिल्कुल नहीं बदलेगा।

**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


जब Delete मेथड में हटाने के लिए कोई प्रभावित हस्ताक्षर नहीं होते हैं, तो स्रोत दस्तावेज़ को पुनः सहेजने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। यदि यह फ़्लैग true (डिफ़ॉल्ट रूप से) पर सेट है, तो दस्तावेज़ संबंधित इतिहास प्रक्रिया लॉग (तारीख और ऑपरेशन प्रकार) के साथ सहेजा जाएगा, भले ही Delete मेथड में हटाने के लिए कोई हस्ताक्षर न हों। जब यह फ़्लैग false पर सेट किया जाता है, तो स्रोत दस्तावेज़ बिल्कुल नहीं बदलेगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Metadata List में एम्बेडेड मानक दस्तावेज़ मेटाडेटा हस्ताक्षर जैसे Author, Owner, दस्तावेज़ निर्माण तिथि, संशोधित तिथि आदि को शामिल करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। यदि यह फ़्लैग false (डिफ़ॉल्ट रूप से) पर सेट है, तो GetDocumentInfo इन मेटाडेटा हस्ताक्षरों को शामिल नहीं करेगा। जब यह फ़्लैग true पर सेट होता है, तो दस्तावेज़ जानकारी इन मानक मेटाडेटा हस्ताक्षरों को शामिल करेगी।

**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Metadata List में एम्बेडेड मानक दस्तावेज़ मेटाडेटा हस्ताक्षर जैसे Author, Owner, दस्तावेज़ निर्माण तिथि, संशोधित तिथि आदि को शामिल करने के लिए फ़्लैग को प्राप्त करता है या सेट करता है। यदि यह फ़्लैग false (डिफ़ॉल्ट रूप से) पर सेट है, तो GetDocumentInfo इन मेटाडेटा हस्ताक्षरों को शामिल नहीं करेगा। जब यह फ़्लैग true पर सेट होता है, तो दस्तावेज़ जानकारी इन मानक मेटाडेटा हस्ताक्षरों को शामिल करेगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


लॉगिंग (Errors, Warnings, Traces) के लिए उपयोग की जाने वाली लॉगर इम्प्लीमेंटेशन। [ILogger](../../com.groupdocs.signature.logging/ilogger).

**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


संदेशों को सीमित करने के लिए लॉगिंग स्तर (All, Traces, Warnings, Errors)। LogLevel। डिफ़ॉल्ट रूप से All स्तर सेट किया जाता है।

**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


संदेशों को सीमित करने के लिए लॉगिंग स्तर (All, Traces, Warnings, Errors)। LogLevel। डिफ़ॉल्ट रूप से All स्तर सेट किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

