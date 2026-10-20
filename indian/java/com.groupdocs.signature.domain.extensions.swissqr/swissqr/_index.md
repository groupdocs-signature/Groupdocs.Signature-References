---
title: "SwissQR"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "SwissQR कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

SwissQR कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | SwissQR का एक उदाहरण बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAmount()](#getAmount--) | भुगतान राशि प्राप्त करता है या सेट करता है। |
|
|  | [setAmount(double value)](#setAmount-double-) | भुगतान राशि प्राप्त करता है या सेट करता है। |
|
|  | [getCurrency()](#getCurrency--) | भुगतान मुद्रा प्राप्त करता है या सेट करता है। |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | भुगतान मुद्रा प्राप्त करता है या सेट करता है। |
|
|  | [getAccount()](#getAccount--) | क्रेडिटर का खाता नंबर प्राप्त करता है या सेट करता है। |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | क्रेडिटर का खाता नंबर प्राप्त करता है या सेट करता है। |
|
|  | [getCreditor()](#getCreditor--) | क्रेडिटर का पता प्राप्त करता है या सेट करता है। |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | क्रेडिटर का पता प्राप्त करता है या सेट करता है। |
|
|  | [getReference()](#getReference--) | क्रेडिटर भुगतान संदर्भ प्राप्त करता है या सेट करता है। |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | क्रेडिटर भुगतान संदर्भ प्राप्त करता है या सेट करता है। |
|
|  | [getDebtor()](#getDebtor--) | लेनदार का पता प्राप्त करता है या सेट करता है। |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | लेनदार का पता प्राप्त करता है या सेट करता है। |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | अतिरिक्त असंरचित संदेश प्राप्त करता है या सेट करता है। |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | अतिरिक्त असंरचित संदेश प्राप्त करता है या सेट करता है। |
|
|  | [getBillInformation()](#getBillInformation--) | अतिरिक्त संरचित बिल जानकारी प्राप्त करता है या सेट करता है। |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | अतिरिक्त संरचित बिल जानकारी प्राप्त करता है या सेट करता है। |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


SwissQR का एक उदाहरण बनाता है।


### getAmount() {#getAmount--}
```
public final double getAmount()
```


भुगतान राशि प्राप्त करता है या सेट करता है।
वैध मान 0.01 और 999,999,999.99 के बीच हैं।
मान: भुगतान राशि।


**Returns:**
डबल
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


भुगतान राशि प्राप्त करता है या सेट करता है।
वैध मान 0.01 और 999,999,999.99 के बीच हैं।
मान: भुगतान राशि।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


भुगतान मुद्रा प्राप्त करता है या सेट करता है।
वैध मान "CHF" और "EUR" हैं।
मान: भुगतान मुद्रा।


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


भुगतान मुद्रा प्राप्त करता है या सेट करता है।
वैध मान "CHF" और "EUR" हैं।
मान: भुगतान मुद्रा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


क्रेडिटर का खाता नंबर प्राप्त करता है या सेट करता है।
खाता नंबर स्विट्ज़रलैंड या लिचेंस्टीन के बैंक के वैध IBAN होने चाहिए।
खाता नंबर में स्पेस की अनुमति है।
मान: लेनदार खाता नंबर।


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


क्रेडिटर का खाता नंबर प्राप्त करता है या सेट करता है।
खाता नंबर स्विट्ज़रलैंड या लिचेंस्टीन के बैंक के वैध IBAN होने चाहिए।
खाता नंबर में स्पेस की अनुमति है।
मान: लेनदार खाता नंबर।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


क्रेडिटर का पता प्राप्त करता है या सेट करता है।
मान: लेनदार का पता।


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


क्रेडिटर का पता प्राप्त करता है या सेट करता है।
मान: लेनदार का पता।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


क्रेडिटर भुगतान संदर्भ प्राप्त करता है या सेट करता है।
SwissQR IBAN के लिए संदर्भ अनिवार्य है, अर्थात् CHxx30000xxxxxx सीमा के IBAN।
CHxx31999xxxxx तक।
यदि निर्दिष्ट किया गया है, तो संदर्भ या तो वैध SwissQR संदर्भ (संबंधित
ISR संदर्भ रूप) या ISO 11649 के अनुसार वैध लेनदार संदर्भ ("RFxxxx") होना चाहिए।
दोनों में स्वरूपण के लिए स्पेस हो सकते हैं।
मान: लेनदार भुगतान संदर्भ।


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


क्रेडिटर भुगतान संदर्भ प्राप्त करता है या सेट करता है।
SwissQR IBAN के लिए संदर्भ अनिवार्य है, अर्थात् CHxx30000xxxxxx सीमा के IBAN।
CHxx31999xxxxx तक।
यदि निर्दिष्ट किया गया है, तो संदर्भ या तो वैध SwissQR संदर्भ (संबंधित
ISR संदर्भ रूप) या ISO 11649 के अनुसार वैध लेनदार संदर्भ ("RFxxxx") होना चाहिए।
दोनों में स्वरूपण के लिए स्पेस हो सकते हैं।
मान: लेनदार भुगतान संदर्भ।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


लेनदार का पता प्राप्त करता है या सेट करता है।
लेनदार वैकल्पिक है। यदि इसे छोड़ दिया जाता है, तो इस फ़ील्ड को null सेट करना या
सभी null या खाली मानों के साथ पता सेट करना ठीक है।
मान: लेनदार का पता।


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


लेनदार का पता प्राप्त करता है या सेट करता है।
लेनदार वैकल्पिक है। यदि इसे छोड़ दिया जाता है, तो इस फ़ील्ड को null सेट करना या
सभी null या खाली मानों के साथ पता सेट करना ठीक है।
मान: लेनदार का पता।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


अतिरिक्त असंरचित संदेश प्राप्त करता है या सेट करता है।
मान: असंरचित संदेश।


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


अतिरिक्त असंरचित संदेश प्राप्त करता है या सेट करता है।
मान: असंरचित संदेश।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


अतिरिक्त संरचित बिल जानकारी प्राप्त करता है या सेट करता है।
मान: संरचित बिल जानकारी।


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


अतिरिक्त संरचित बिल जानकारी प्राप्त करता है या सेट करता है।
मान: संरचित बिल जानकारी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

