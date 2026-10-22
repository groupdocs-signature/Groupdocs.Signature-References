---
title: "पैडिंग"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "तत्व से जुड़ी पैडिंग या मार्जिन जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

तत्व से जुड़ी पैडिंग या मार्जिन जानकारी का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Padding()](#Padding--) | शून्य मानों का उपयोग करके Padding क्लास का नया उदाहरण प्रारंभ करता है। |
| [Padding(int all)](#Padding-int-) | सभी किनारों के लिए प्रदान किए गए पैडिंग आकार का उपयोग करके Padding क्लास का नया उदाहरण प्रारंभ करता है। |
| [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | प्रदान किए गए पैडिंग आकारों का उपयोग करके Padding क्लास का नया उदाहरण प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Empty](#Empty) | कोई पैडिंग नहीं वाला Padding ऑब्जेक्ट प्रदान करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAll()](#getAll--) | सभी किनारों के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [setAll(int value)](#setAll-int-) | सभी किनारों के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [getLeft()](#getLeft--) | बाएँ किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [setLeft(int value)](#setLeft-int-) | बाएँ किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [getRight()](#getRight--) | दाएँ किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [setRight(int value)](#setRight-int-) | दाएँ किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [getTop()](#getTop--) | ऊपरी किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [setTop(int value)](#setTop-int-) | ऊपरी किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [getBottom()](#getBottom--) | निचले किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [setBottom(int value)](#setBottom-int-) | निचले किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है। |
| [getHorizontal()](#getHorizontal--) | दाएँ और बाएँ किनारों के लिए संयुक्त पैडिंग प्राप्त करता है। |
| [getVertical()](#getVertical--) | ऊपरी और निचले किनारों के लिए संयुक्त पैडिंग प्राप्त करता है। |
| [deepClone()](#deepClone--) | इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है। |
| [toString()](#toString--) | स्ट्रिंग में रूपांतरण को ओवरराइड करता है |
### Padding() {#Padding--}
```
public Padding()
```


शून्य मानों का उपयोग करके Padding क्लास का नया उदाहरण प्रारंभ करता है।

### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


सभी किनारों के लिए प्रदान किए गए पैडिंग आकार का उपयोग करके Padding क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सभी | int | सभी किनारों के लिए पैडिंग में उपयोग किए जाने वाले माप इकाइयों की संख्या। |

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


प्रदान किए गए पैडिंग आकारों का उपयोग करके Padding क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बाएँ | int | बाएँ पैडिंग आकार। |
| दायाँ | int | दायाँ पैडिंग आकार। |
| ऊपर | int | ऊपरी पैडिंग आकार। |
| नीचा | int | नीचे की पैडिंग आकार। |

### Empty {#Empty}
```
public static final Padding Empty
```


कोई पैडिंग नहीं वाला Padding ऑब्जेक्ट प्रदान करता है।

### getAll() {#getAll--}
```
public final int getAll()
```


सभी किनारों के लिए पैडिंग मान प्राप्त करता है या सेट करता है। बाएँ या ऊपर जैसी किसी भी आंशिक किनारे को बदलने से यह गुण 0 के बराबर हो जाता है;

**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


सभी किनारों के लिए पैडिंग मान प्राप्त करता है या सेट करता है। बाएँ या ऊपर जैसी किसी भी आंशिक किनारे को बदलने से यह गुण 0 के बराबर हो जाता है;

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


बाएँ किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है।

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


बाएँ किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


दाएँ किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है।

**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


दाएँ किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


ऊपरी किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है।

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


ऊपरी किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


निचले किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है।

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


निचले किनारे के लिए पैडिंग मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


दाएँ और बाएँ किनारों के लिए संयुक्त पैडिंग प्राप्त करता है।

**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


ऊपरी और निचले किनारों के लिए संयुक्त पैडिंग प्राप्त करता है।

**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है।

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग में रूपांतरण को ओवरराइड करता है

**Returns:**
java.lang.String -
