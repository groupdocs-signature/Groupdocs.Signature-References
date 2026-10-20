---
title: "Corners"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "एक वर्ग ग्राफ़िकल ऑब्जेक्ट के कोनों का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

एक वर्ग ग्राफ़िकल ऑब्जेक्ट के कोनों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Corners()](#Corners--) | शून्य मानों का उपयोग करके Corners क्लास का नया इंस्टेंस आरंभ करता है। |
|
|  | [Corners(double all)](#Corners-double-) | सभी कोर्नर्स के लिए प्रदान किए गए मान का उपयोग करके Corners क्लास का नया इंस्टेंस आरंभ करता है। |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | प्रदान किए गए मानों का उपयोग करके Corners क्लास का नया इंस्टेंस आरंभ करता है। |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Empty](#Empty) | कोई डेटा नहीं वाले Corners ऑब्जेक्ट प्रदान करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAll()](#getAll--) | सभी कोर्नर्स के मान को प्राप्त करता है या सेट करता है। |
|
|  | [setAll(double value)](#setAll-double-) | सभी कोर्नर्स के मान को प्राप्त करता है या सेट करता है। |
|
|  | [getTopLeft()](#getTopLeft--) | ऊपरी बाएँ कोर्नर का मान प्राप्त करता है या सेट करता है। |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | ऊपरी बाएँ कोर्नर का मान प्राप्त करता है या सेट करता है। |
|
|  | [getTopRight()](#getTopRight--) | शीर्ष दाएँ कोने का मान प्राप्त करता है या सेट करता है। |
|
|  | [setTopRight(double value)](#setTopRight-double-) | शीर्ष दाएँ कोने का मान प्राप्त करता है या सेट करता है। |
|
|  | [getBottomLeft()](#getBottomLeft--) | निचले बाएँ कोने का मान प्राप्त करता है या सेट करता है। |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | निचले बाएँ कोने का मान प्राप्त करता है या सेट करता है। |
|
|  | [getBottomRight()](#getBottomRight--) | निचले दाएँ कोने का मान प्राप्त करता है या सेट करता है। |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | निचले दाएँ कोने का मान प्राप्त करता है या सेट करता है। |
|
|  | [deepClone()](#deepClone--) | इस वस्तु की एक प्रति प्राप्त करता है। |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | equals मेथड को ओवरराइड करें |
|
|  | [hashCode()](#hashCode--) | अद्वितीय हैश कोड मान प्राप्त करने को ओवरराइड करता है |
|
|  | [toString()](#toString--) | स्ट्रिंग में रूपांतरण को ओवरराइड करता है। |
|
### Corners() {#Corners--}
```
public Corners()
```


शून्य मानों का उपयोग करके Corners क्लास का नया इंस्टेंस आरंभ करता है।


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


सभी कोर्नर्स के लिए प्रदान किए गए मान का उपयोग करके Corners क्लास का नया इंस्टेंस आरंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | सभी | डबल | सभी कोनों के लिए पैडिंग के रूप में उपयोग किया जाने वाला मान। |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


प्रदान किए गए मानों का उपयोग करके Corners क्लास का नया इंस्टेंस आरंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | topLeft | डबल | बाएँ ऊपर कोने का मान। |
|
|  | topRight | डबल | दाएँ ऊपर कोने का मान। |
|
|  | bottomLeft | डबल | बाएँ नीचे कोने का मान। |
|
|  | bottomRight | डबल | दाएँ नीचे कोने का मान। |
|

### Empty {#Empty}
```
public static final Corners Empty
```


कोई डेटा नहीं वाले Corners ऑब्जेक्ट प्रदान करता है।


### getAll() {#getAll--}
```
public final double getAll()
```


सभी कोर्नर्स के मान को प्राप्त करता है या सेट करता है।
किसी भी आंशिक कोने जैसे शीर्ष दाएँ कोने को बदलने से यह प्रॉपर्टी 0 के बराबर हो जाती है;


**Returns:**
डबल
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


सभी कोर्नर्स के मान को प्राप्त करता है या सेट करता है।
किसी भी आंशिक कोने जैसे शीर्ष दाएँ कोने को बदलने से यह प्रॉपर्टी 0 के बराबर हो जाती है;


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


ऊपरी बाएँ कोर्नर का मान प्राप्त करता है या सेट करता है।


**Returns:**
डबल
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


ऊपरी बाएँ कोर्नर का मान प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


शीर्ष दाएँ कोने का मान प्राप्त करता है या सेट करता है।


**Returns:**
डबल
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


शीर्ष दाएँ कोने का मान प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


निचले बाएँ कोने का मान प्राप्त करता है या सेट करता है।


**Returns:**
डबल
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


निचले बाएँ कोने का मान प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


निचले दाएँ कोने का मान प्राप्त करता है या सेट करता है।


**Returns:**
डबल
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


निचले दाएँ कोने का मान प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


इस वस्तु की एक प्रति प्राप्त करता है।


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


equals मेथड को ओवरराइड करें


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | ऑब्जेक्ट | java.lang.Object | तुलना करने के लिए इंस्टेंस। |
|

**Returns:**
boolean - यदि वस्तुओं के गुण समान हैं तो true लौटाता है।

### hashCode() {#hashCode--}
```
public int hashCode()
```


अद्वितीय हैश कोड मान प्राप्त करने को ओवरराइड करता है


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग में रूपांतरण को ओवरराइड करता है।


**Returns:**
java.lang.String -
