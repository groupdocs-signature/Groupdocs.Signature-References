---
title: "StampSignOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "स्टैम्प हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 17
url: /hi/nodejs-java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

स्टैम्प हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [StampSignOptions()](#StampSignOptions--) | डिफ़ॉल्ट मानों के साथ StampSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | संरेखण विकल्पों के साथ StampSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getStampType()](#getStampType--) | स्टैम्प प्रकार को प्राप्त करता है या सेट करता है। |
| [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | स्टैम्प प्रकार को प्राप्त करता है या सेट करता है। |
| [getOuterLines()](#getOuterLines--) | एकाग्र वृत्तों के रूप में रेंडर की गई बाहरी रेखाओं की सूची। |
| [getInnerLines()](#getInnerLines--) | आयतों के सेट के रूप में रेंडर की गई आंतरिक रेखाओं की सूची। |
| [getBackground()](#getBackground--) | स्टैम्प पृष्ठभूमि को प्राप्त करता है या सेट करता है। |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | स्टैम्प पृष्ठभूमि को प्राप्त करता है या सेट करता है। |
| [getBackgroundColor()](#getBackgroundColor--) | हस्ताक्षर का पृष्ठभूमि रंग प्राप्त करता है या सेट करता है। |
| [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | हस्ताक्षर का पृष्ठभूमि रंग प्राप्त करता है या सेट करता है। |
| [getBackgroundBrush()](#getBackgroundBrush--) | हस्ताक्षर पृष्ठभूमि ब्रश को प्राप्त करता है या सेट करता है। |
| [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | हस्ताक्षर पृष्ठभूमि ब्रश को प्राप्त करता है या सेट करता है। |
| [getBackgroundColorCropType()](#getBackgroundColorCropType--) | हस्ताक्षर की पृष्ठभूमि रंग क्रॉप प्रकार को प्राप्त करता है या सेट करता है। |
| [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | हस्ताक्षर की पृष्ठभूमि रंग क्रॉप प्रकार को प्राप्त करता है या सेट करता है। |
| [getBackgroundImageCropType()](#getBackgroundImageCropType--) | हस्ताक्षर की पृष्ठभूमि छवि क्रॉप प्रकार को प्राप्त करता है या सेट करता है। |
| [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | हस्ताक्षर की पृष्ठभूमि छवि क्रॉप प्रकार को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें |
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


डिफ़ॉल्ट मानों के साथ StampSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


संरेखण विकल्पों के साथ StampSignOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बाएँ | int | स्टैम्प हस्ताक्षर के बाएँ ऊपर किनारे का x-निर्देशांक |
| ऊपर | int | स्टैम्प हस्ताक्षर के बाएँ ऊपर किनारे का y-निर्देशांक |
| चौड़ाई | int | स्टैम्प हस्ताक्षर की चौड़ाई |
| ऊँचाई | int | स्टैम्प हस्ताक्षर की ऊँचाई |

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


स्टैम्प प्रकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान गोल है।

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


स्टैम्प प्रकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान गोल है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


एकाग्र वृत्तों के रूप में रेंडर की गई बाहरी रेखाओं की सूची।

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


आयतों के सेट के रूप में रेंडर की गई आंतरिक रेखाओं की सूची।

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


स्टैम्प पृष्ठभूमि को प्राप्त करता है या सेट करता है।

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


स्टैम्प पृष्ठभूमि को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


हस्ताक्षर का पृष्ठभूमि रंग प्राप्त करता है या सेट करता है।

**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


हस्ताक्षर का पृष्ठभूमि रंग प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


हस्ताक्षर पृष्ठभूमि ब्रश को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है।

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


हस्ताक्षर पृष्ठभूमि ब्रश को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


हस्ताक्षर की पृष्ठभूमि रंग क्रॉप प्रकार को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


हस्ताक्षर की पृष्ठभूमि रंग क्रॉप प्रकार को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


हस्ताक्षर की पृष्ठभूमि छवि क्रॉप प्रकार को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


हस्ताक्षर की पृष्ठभूमि छवि क्रॉप प्रकार को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग रूपांतरण को ओवरराइड करें

**Returns:**
java.lang.String -
