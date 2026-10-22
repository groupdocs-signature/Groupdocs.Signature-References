---
title: "कोने"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "एक वर्ग ग्राफिकल ऑब्जेक्ट के कोनों का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

एक वर्ग ग्राफिकल ऑब्जेक्ट के कोनों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Corners()](#Corners--) | शून्य मानों का उपयोग करके Corners क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Corners(double all)](#Corners-double-) | सभी कोनों के लिए प्रदान किए गए मान का उपयोग करके Corners क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | प्रदान किए गए मानों का उपयोग करके Corners क्लास का नया इंस्टेंस प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Empty](#Empty) | कोई डेटा नहीं वाला Corners ऑब्जेक्ट प्रदान करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAll()](#getAll--) | सभी कोनों के मान को प्राप्त करता है या सेट करता है। |
| [setAll(double value)](#setAll-double-) | सभी कोनों के मान को प्राप्त करता है या सेट करता है। |
| [getTopLeft()](#getTopLeft--) | ऊपरी बाएँ कोने के मान को प्राप्त करता है या सेट करता है। |
| [setTopLeft(double value)](#setTopLeft-double-) | ऊपरी बाएँ कोने के मान को प्राप्त करता है या सेट करता है। |
| [getTopRight()](#getTopRight--) | ऊपरी दाएँ कोने के मान को प्राप्त करता है या सेट करता है। |
| [setTopRight(double value)](#setTopRight-double-) | ऊपरी दाएँ कोने के मान को प्राप्त करता है या सेट करता है। |
| [getBottomLeft()](#getBottomLeft--) | निचले बाएँ कोने के मान को प्राप्त करता है या सेट करता है। |
| [setBottomLeft(double value)](#setBottomLeft-double-) | निचले बाएँ कोने के मान को प्राप्त करता है या सेट करता है। |
| [getBottomRight()](#getBottomRight--) | निचले दाएँ कोने के मान को प्राप्त करता है या सेट करता है। |
| [setBottomRight(double value)](#setBottomRight-double-) | निचले दाएँ कोने के मान को प्राप्त करता है या सेट करता है। |
| [deepClone()](#deepClone--) | इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | equals मेथड को ओवरराइड करें |
| [hashCode()](#hashCode--) | यूनिक हैश कोड वैल्यू प्राप्त करने को ओवरराइड करता है |
| [toString()](#toString--) | स्ट्रिंग में रूपांतरण को ओवरराइड करता है। |
### Corners() {#Corners--}
```
public Corners()
```


शून्य मानों का उपयोग करके Corners क्लास का नया इंस्टेंस प्रारंभ करता है।

### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


सभी कोनों के लिए प्रदान किए गए मान का उपयोग करके Corners क्लास का नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सभी | double | सभी कोनों के लिए पैडिंग हेतु उपयोग किया जाने वाला मान। |

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


प्रदान किए गए मानों का उपयोग करके Corners क्लास का नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| topLeft | double | ऊपरी बाएँ कोने का मान। |
| topRight | double | ऊपरी दाएँ कोने का मान। |
| bottomLeft | double | निचले बाएँ कोने का मान। |
| bottomRight | double | निचले दाएँ कोने का मान। |

### Empty {#Empty}
```
public static final Corners Empty
```


कोई डेटा नहीं वाला Corners ऑब्जेक्ट प्रदान करता है।

### getAll() {#getAll--}
```
public final double getAll()
```


सभी कोनों के मान को प्राप्त करता है या सेट करता है। किसी भी आंशिक कोने, जैसे ऊपरी दाएँ, को बदलने से यह प्रॉपर्टी 0 हो जाती है;

**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


सभी कोनों के मान को प्राप्त करता है या सेट करता है। किसी भी आंशिक कोने, जैसे ऊपरी दाएँ, को बदलने से यह प्रॉपर्टी 0 हो जाती है;

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


ऊपरी बाएँ कोने के मान को प्राप्त करता है या सेट करता है।

**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


ऊपरी बाएँ कोने के मान को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


ऊपरी दाएँ कोने के मान को प्राप्त करता है या सेट करता है।

**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


ऊपरी दाएँ कोने के मान को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


निचले बाएँ कोने के मान को प्राप्त करता है या सेट करता है।

**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


निचले बाएँ कोने के मान को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


निचले दाएँ कोने के मान को प्राप्त करता है या सेट करता है।

**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


निचले दाएँ कोने के मान को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है।

**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


equals मेथड को ओवरराइड करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए इंस्टेंस। |

**Returns:**
boolean - यदि वस्तुओं की गुणधर्म समान हों तो true लौटाता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


यूनिक हैश कोड वैल्यू प्राप्त करने को ओवरराइड करता है

**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग में रूपांतरण को ओवरराइड करता है।

**Returns:**
java.lang.String -
