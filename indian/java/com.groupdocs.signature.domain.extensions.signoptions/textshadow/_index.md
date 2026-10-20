---
title: "TextShadow"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "टेक्स्ट हस्ताक्षर के लिए टेक्स्ट शैडो प्रॉपर्टीज़ का प्रतिनिधित्व करता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

टेक्स्ट हस्ताक्षर के लिए टेक्स्ट शैडो प्रॉपर्टीज़ का प्रतिनिधित्व करता है।
परिणाम हस्ताक्षर प्रकार और दस्तावेज़ फ़ॉर्मेट पर निर्भर कर सकता है।
सभी समर्थित दस्तावेज़ प्रकारों के लिए TextAsImage हस्ताक्षर के साथ उपयोग करने हेतु TextShadow की सिफ़ारिश की जाती है।
साथ ही सरल TextSignature और TextSignature को Cells (.xslx) और Slides (.pptx) के लिए वॉटरमार्क के रूप में उपयोग किया जा सकता है।
Words (.docx) के लिए सरल TextSignature भी अनुशंसित है, लेकिन इसकी कार्यक्षमता सीमित है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | डिफ़ॉल्ट विकल्पों के साथ TextShadow बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getDistance()](#getDistance--) | टेक्स्ट से शैडो तक की दूरी प्राप्त करता है या सेट करता है। |
|
|  | [setDistance(double value)](#setDistance-double-) | टेक्स्ट से शैडो तक की दूरी प्राप्त करता है या सेट करता है। |
|
|  | [getAngle()](#getAngle--) | टेक्स्ट के सापेक्ष शैडो रखने के लिए कोण प्राप्त करता है या सेट करता है। |
|
|  | [setAngle(double value)](#setAngle-double-) | टेक्स्ट के सापेक्ष शैडो रखने के लिए कोण प्राप्त करता है या सेट करता है। |
|
|  | [getColor()](#getColor--) | शैडो का रंग प्राप्त करता है या सेट करता है। |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | शैडो का रंग प्राप्त करता है या सेट करता है। |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | शैडो का रंग प्राप्त करता है या सेट करता है। |
|
|  | [getTransparency()](#getTransparency--) | शैडो की पारदर्शिता प्राप्त करता है या सेट करता है। |
|
|  | [setTransparency(double value)](#setTransparency-double-) | शैडो की पारदर्शिता प्राप्त करता है या सेट करता है। |
|
|  | [getBlur()](#getBlur--) | शैडो की धुंधलापन प्राप्त करता है या सेट करता है। |
|
|  | [setBlur(double value)](#setBlur-double-) | शैडो की धुंधलापन प्राप्त करता है या सेट करता है। |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


डिफ़ॉल्ट विकल्पों के साथ TextShadow बनाता है।


### getDistance() {#getDistance--}
```
public final double getDistance()
```


टेक्स्ट से शैडो तक की दूरी प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान 1 है।


**Returns:**
डबल
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


टेक्स्ट से शैडो तक की दूरी प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान 1 है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


टेक्स्ट के सापेक्ष शैडो रखने के लिए कोण प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान 0 है।


**Returns:**
डबल
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


टेक्स्ट के सापेक्ष शैडो रखने के लिए कोण प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान 0 है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


शैडो का रंग प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान काला है।


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


शैडो का रंग प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान काला है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


शैडो का रंग प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान काला है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


शैडो की पारदर्शिता प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान 0 है।


**Returns:**
डबल
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


शैडो की पारदर्शिता प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान 0 है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


शैडो की धुंधलापन प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान 4 है।


**Returns:**
डबल
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


शैडो की धुंधलापन प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट मान 4 है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

