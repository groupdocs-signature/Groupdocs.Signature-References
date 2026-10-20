---
title: "StampSignOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "स्टैम्प हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.signature.options.sign/stampsignoptions/
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
|  | [StampSignOptions()](#StampSignOptions--) | डिफ़ॉल्ट मानों के साथ StampSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | एलाइमेंट विकल्पों के साथ StampSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getStampType()](#getStampType--) | स्टैम्प प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | स्टैम्प प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [getOuterLines()](#getOuterLines--) | बाहरी लाइनों की सूची जो समकेंद्रित वृत्तों के रूप में रेंडर की जाती है। |
|
|  | [getInnerLines()](#getInnerLines--) | आंतरिक लाइनों की सूची जो आयतों के सेट के रूप में रेंडर की जाती है। |
|
|  | [getBackground()](#getBackground--) | स्टैम्प बैकग्राउंड को प्राप्त करता है या सेट करता है। |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | स्टैम्प बैकग्राउंड को प्राप्त करता है या सेट करता है। |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | हस्ताक्षर का पृष्ठभूमि रंग प्राप्त करता है या सेट करता है। |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | हस्ताक्षर का पृष्ठभूमि रंग प्राप्त करता है या सेट करता है। |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | हस्ताक्षर बैकग्राउंड ब्रश को प्राप्त करता है या सेट करता है। |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | हस्ताक्षर बैकग्राउंड ब्रश को प्राप्त करता है या सेट करता है। |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | हस्ताक्षर के बैकग्राउंड कलर क्रॉप प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | हस्ताक्षर के बैकग्राउंड कलर क्रॉप प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | हस्ताक्षर के बैकग्राउंड इमेज क्रॉप प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | हस्ताक्षर के बैकग्राउंड इमेज क्रॉप प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


डिफ़ॉल्ट मानों के साथ StampSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


एलाइमेंट विकल्पों के साथ StampSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | बाएँ | int | स्टैम्प सिग्नेचर के बाएँ शीर्ष किनारे का x-कोऑर्डिनेट |
|
|  | ऊपर | int | स्टैम्प सिग्नेचर के बाएँ शीर्ष किनारे का y-कोऑर्डिनेट |
|
|  | चौड़ाई | int | स्टैम्प सिग्नेचर की चौड़ाई |
|
|  | ऊँचाई | int | स्टैम्प सिग्नेचर की ऊँचाई |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


स्टैम्प प्रकार को प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट रूप से मान Round है।


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


स्टैम्प प्रकार को प्राप्त करता है या सेट करता है।
डिफ़ॉल्ट रूप से मान Round है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


बाहरी लाइनों की सूची जो समकेंद्रित वृत्तों के रूप में रेंडर की जाती है।


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


आंतरिक लाइनों की सूची जो आयतों के सेट के रूप में रेंडर की जाती है।


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


स्टैम्प बैकग्राउंड को प्राप्त करता है या सेट करता है।


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


स्टैम्प बैकग्राउंड को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


हस्ताक्षर बैकग्राउंड ब्रश को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से मान null है।


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


हस्ताक्षर बैकग्राउंड ब्रश को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से मान null है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


हस्ताक्षर के बैकग्राउंड कलर क्रॉप प्रकार को प्राप्त करता है या सेट करता है।


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


हस्ताक्षर के बैकग्राउंड कलर क्रॉप प्रकार को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


हस्ताक्षर के बैकग्राउंड इमेज क्रॉप प्रकार को प्राप्त करता है या सेट करता है।


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


हस्ताक्षर के बैकग्राउंड इमेज क्रॉप प्रकार को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण


**Returns:**
java.lang.String -
