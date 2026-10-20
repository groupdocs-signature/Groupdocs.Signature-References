---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code द्वितीयक और अतिरिक्त डेटा संग्रहीत करने के लिए क्लास।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) द्वितीयक और अतिरिक्त डेटा संग्रहीत करने के लिए क्लास।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | डिफ़ॉल्ट ctor() |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | समाप्ति तिथि प्रारूप की पहचान करता है। |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | समाप्ति तिथि प्रारूप की पहचान करता है। |
|
|  | [getExpiryDate()](#getExpiryDate--) | समाप्ति तिथि की पहचान करता है। |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | समाप्ति तिथि की पहचान करता है। |
|
|  | [getLotNumber()](#getLotNumber--) | लॉट या बैच नंबर की पहचान करता है। |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | लॉट या बैच नंबर की पहचान करता है। |
|
|  | [getSerialNumber()](#getSerialNumber--) | सीरियल नंबर की पहचान करता है। |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | सीरियल नंबर की पहचान करता है। |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | निर्माण तिथि की पहचान करता है। |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | निर्माण तिथि की पहचान करता है। |
|
|  | [getQuantity()](#getQuantity--) | मात्रा की पहचान करता है, 0 से 500 के बीच पूर्णांक मान होना चाहिए। |
|
|  | [setQuantity(int value)](#setQuantity-int-) | मात्रा की पहचान करता है, 0 से 500 के बीच पूर्णांक मान होना चाहिए। |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | आउटपुट स्ट्रिंग में लिंक कैरेक्टर की पहचान करता है। |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | आउटपुट स्ट्रिंग में लिंक कैरेक्टर की पहचान करता है। |
|
|  | [deepClone()](#deepClone--) | इस वस्तु की एक प्रति प्राप्त करता है। |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


डिफ़ॉल्ट ctor()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


समाप्ति तिथि प्रारूप की पहचान करता है।


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


समाप्ति तिथि प्रारूप की पहचान करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो यह उपयोग किया जाएगा।


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो यह उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


लॉट या बैच नंबर की पहचान करता है।
लॉट/बैच नंबर 18 अक्षरों तक की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


लॉट या बैच नंबर की पहचान करता है।
लॉट/बैच नंबर 18 अक्षरों तक की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


सीरियल नंबर की पहचान करता है।
सीरियल नंबर 18 अक्षरों तक की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


सीरियल नंबर की पहचान करता है।
सीरियल नंबर 18 अक्षरों तक की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


निर्माण तिथि की पहचान करता है।
निर्माण तिथि को इस फ़ील्ड का उपयोग न करने के लिए DateTime.MinValue पर सेट किया जा सकता है।
डिफ़ॉल्ट मान: DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


निर्माण तिथि की पहचान करता है।
निर्माण तिथि को इस फ़ील्ड का उपयोग न करने के लिए DateTime.MinValue पर सेट किया जा सकता है।
डिफ़ॉल्ट मान: DateTime.MinValue


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


मात्रा की पहचान करता है, 0 से 500 के बीच पूर्णांक मान होना चाहिए।
मात्रा को इस फ़ील्ड का उपयोग न करने के लिए -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


मात्रा की पहचान करता है, 0 से 500 के बीच पूर्णांक मान होना चाहिए।
मात्रा को इस फ़ील्ड का उपयोग न करने के लिए -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


आउटपुट स्ट्रिंग में लिंक कैरेक्टर की पहचान करता है।


**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


आउटपुट स्ट्रिंग में लिंक कैरेक्टर की पहचान करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


इस वस्तु की एक प्रति प्राप्त करता है।


**Returns:**
java.lang.Object
