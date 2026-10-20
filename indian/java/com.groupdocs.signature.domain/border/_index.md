---
title: "सीमा"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "Border लाइन गुणों को रखने के लिए इंस्टेंस।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Border लाइन गुणों को रखने के लिए इंस्टेंस।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Border()](#Border--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | हस्ताक्षर सीमा शैली प्राप्त करता है या सेट करता है। |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | हस्ताक्षर सीमा शैली प्राप्त करता है या सेट करता है। |
|
|  | [getTransparency()](#getTransparency--) | हस्ताक्षर सीमा की पारदर्शिता प्राप्त करता है या सेट करता है (मान 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक)। |
|
|  | [setTransparency(double value)](#setTransparency-double-) | हस्ताक्षर सीमा की पारदर्शिता प्राप्त करता है या सेट करता है (मान 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक)। |
|
|  | [getWeight()](#getWeight--) | हस्ताक्षर सीमा का वजन प्राप्त करता है या सेट करता है। |
|
|  | [setWeight(double value)](#setWeight-double-) | हस्ताक्षर सीमा का वजन प्राप्त करता है या सेट करता है। |
|
|  | [getColor()](#getColor--) | हस्ताक्षर की सीमा का रंग प्राप्त करता है या सेट करता है। |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | हस्ताक्षर की सीमा का रंग प्राप्त करता है या सेट करता है। |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | हस्ताक्षर की सीमा का रंग प्राप्त करता है या सेट करता है। |
|
|  | [getVisible()](#getVisible--) | सीमा की दृश्यता प्राप्त करता है या सेट करता है। |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | IClonable इंटरफ़ेस लागू करें। |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


हस्ताक्षर सीमा शैली प्राप्त करता है या सेट करता है।


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


हस्ताक्षर सीमा शैली प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


हस्ताक्षर सीमा की पारदर्शिता प्राप्त करता है या सेट करता है (मान 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक)।


**Returns:**
डबल
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


हस्ताक्षर सीमा की पारदर्शिता प्राप्त करता है या सेट करता है (मान 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


हस्ताक्षर सीमा का वजन प्राप्त करता है या सेट करता है।


**Returns:**
डबल
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


हस्ताक्षर सीमा का वजन प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


हस्ताक्षर की सीमा का रंग प्राप्त करता है या सेट करता है।


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


हस्ताक्षर की सीमा का रंग प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


हस्ताक्षर की सीमा का रंग प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


सीमा की दृश्यता प्राप्त करता है या सेट करता है।


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


IClonable इंटरफ़ेस लागू करें।


**Returns:**
java.lang.Object - समान गुणों के साथ नया बनाया गया Border इंस्टेंस।

