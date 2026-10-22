---
title: "BaseSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "सिग्नेचर के लिए बेस क्लास का वर्णन करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

सिग्नेचर के लिए बेस क्लास का वर्णन करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSignatureType()](#getSignatureType--) | हस्ताक्षर का प्रकार निर्दिष्ट करता है। |
| [getPageNumber()](#getPageNumber--) | हस्ताक्षर जिस पृष्ठ पर मिला, उसे निर्दिष्ट करता है। |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | हस्ताक्षर जिस पृष्ठ पर मिला, उसे निर्दिष्ट करता है। |
| [getSignatureId()](#getSignatureId--) | दस्तावेज़ में हस्ताक्षर को अपडेट या डिलीट विधियों के माध्यम से संशोधित करने के लिए अद्वितीय हस्ताक्षर पहचानकर्ता। |
| [isSignature()](#isSignature--) | यह संकेत करने के लिए फ़्लैग प्राप्त करें या सेट करें कि यह घटक हस्ताक्षर है या दस्तावेज़ सामग्री। |
| [setSignature(boolean value)](#setSignature-boolean-) | यह संकेत करने के लिए फ़्लैग प्राप्त करें या सेट करें कि यह घटक हस्ताक्षर है या दस्तावेज़ सामग्री। |
| [getDeleted()](#getDeleted--) | यह संकेत करने के लिए फ़्लैग प्राप्त करें या सेट करें कि यह हस्ताक्षर दस्तावेज़ से हटाया गया था। |
| [getCreatedOn()](#getCreatedOn--) | हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें। |
| [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें। |
| [getModifiedOn()](#getModifiedOn--) | हस्ताक्षर संशोधन तिथि प्राप्त करें या सेट करें। |
| [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | हस्ताक्षर संशोधन तिथि प्राप्त करें या सेट करें। |
| [getTop()](#getTop--) | हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है। |
| [setTop(int value)](#setTop-int-) | हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है। |
| [getLeft()](#getLeft--) | हस्ताक्षर की बायाँ स्थिति निर्दिष्ट करता है। |
| [setLeft(int value)](#setLeft-int-) | हस्ताक्षर की बायाँ स्थिति निर्दिष्ट करता है। |
| [getWidth()](#getWidth--) | हस्ताक्षर की चौड़ाई निर्दिष्ट करता है। |
| [setWidth(int value)](#setWidth-int-) | हस्ताक्षर की चौड़ाई निर्दिष्ट करता है। |
| [getHeight()](#getHeight--) | हस्ताक्षर की ऊँचाई निर्दिष्ट करता है। |
| [setHeight(int value)](#setHeight-int-) | हस्ताक्षर की ऊँचाई निर्दिष्ट करता है। |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
| [toString()](#toString--) |  |
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


हस्ताक्षर का प्रकार निर्दिष्ट करता है। डिजिटल हस्ताक्षर में यह प्रॉपर्टी होगी।

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


हस्ताक्षर जिस पृष्ठ पर मिला, उसे निर्दिष्ट करता है।

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


हस्ताक्षर जिस पृष्ठ पर मिला, उसे निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


दस्तावेज़ में हस्ताक्षर को अपडेट या डिलीट विधियों के माध्यम से संशोधित करने के लिए अद्वितीय हस्ताक्षर पहचानकर्ता। यह प्रॉपर्टी साइन या सर्च विधि कॉल होने के बाद स्वचालित रूप से सेट हो जाएगी। यदि यह प्रॉपर्टी पहले सहेजी गई थी, तो इसे हस्ताक्षर को नियंत्रित करने के लिए मैन्युअल रूप से सेट किया जा सकता है।

**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


यह संकेत करने के लिए फ़्लैग प्राप्त करें या सेट करें कि यह घटक हस्ताक्षर है या दस्तावेज़ सामग्री। यह प्रॉपर्टी अपडेट विधि के साथ उपयोग की जाती है ताकि तत्व को हस्ताक्षर (सही) या दस्तावेज़ तत्व (गलत) के रूप में सेट किया जा सके।

**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


यह संकेत करने के लिए फ़्लैग प्राप्त करें या सेट करें कि यह घटक हस्ताक्षर है या दस्तावेज़ सामग्री। यह प्रॉपर्टी अपडेट विधि के साथ उपयोग की जाती है ताकि तत्व को हस्ताक्षर (सही) या दस्तावेज़ तत्व (गलत) के रूप में सेट किया जा सके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


यह संकेत करने के लिए फ़्लैग प्राप्त करें या सेट करें कि यह हस्ताक्षर दस्तावेज़ से हटाया गया था। यह प्रॉपर्टी केवल दस्तावेज़ इतिहास लॉग रिकॉर्ड्स के लिए उपयोग की जाती है ताकि हटाए गए हस्ताक्षरों की सूची रखी जा सके।

**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें।

**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


हस्ताक्षर निर्माण तिथि प्राप्त करें या सेट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


हस्ताक्षर संशोधन तिथि प्राप्त करें या सेट करें।

**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


हस्ताक्षर संशोधन तिथि प्राप्त करें या सेट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है।

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


हस्ताक्षर की शीर्ष स्थिति निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


हस्ताक्षर की बायाँ स्थिति निर्दिष्ट करता है।

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


हस्ताक्षर की बायाँ स्थिति निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


हस्ताक्षर की चौड़ाई निर्दिष्ट करता है।

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


हस्ताक्षर की चौड़ाई निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


हस्ताक्षर की ऊँचाई निर्दिष्ट करता है।

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


हस्ताक्षर की ऊँचाई निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| हस्ताक्षर | java.lang.Object | तुलना के लिए हस्ताक्षर ऑब्जेक्ट। |

**Returns:**
boolean - यदि पास किया गया हस्ताक्षर ऑब्जेक्ट समान प्रकार का है और उसकी सभी गुण इस इंस्टेंस की गुणों के बराबर हैं तो true लौटाता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode मेथड को ओवरराइड करता है।

**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
