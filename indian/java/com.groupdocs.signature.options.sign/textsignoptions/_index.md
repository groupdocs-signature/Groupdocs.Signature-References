---
title: "TextSignOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "टेक्स्ट हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

टेक्स्ट हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | डिफ़ॉल्ट वैल्यूज़ के साथ SignTextOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | टेक्स्ट के साथ SignTextOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getLeft()](#getLeft--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाएँ X स्थिति माप मानों में |
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType प्रॉपर्टी)।
|
|  | [setLeft(int value)](#setLeft-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाएँ X स्थिति माप मानों में |
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType प्रॉपर्टी)।
|
|  | [getTop()](#getTop--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति माप मानों में |
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType प्रॉपर्टी)।
|
|  | [setTop(int value)](#setTop-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति माप मानों में |
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType प्रॉपर्टी)।
|
|  | [getWidth()](#getWidth--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई माप मानों में |
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType प्रॉपर्टी).
|
|  | [setWidth(int value)](#setWidth-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई माप मानों में |
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType प्रॉपर्टी).
|
|  | [getHeight()](#getHeight--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की ऊँचाई माप मानों में |
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType प्रॉपर्टी).
|
|  | [setHeight(int value)](#setHeight-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर की ऊँचाई माप मानों में |
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType प्रॉपर्टी).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | बाएँ और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | बाएँ और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | चौड़ाई और ऊँचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | चौड़ाई और ऊँचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
|
|  | [getStretch()](#getStretch--) | दस्तावेज़ पृष्ठ पर स्ट्रेच मोड। |
|
|  | [setStretch(int value)](#setStretch-int-) | दस्तावेज़ पृष्ठ पर स्ट्रेच मोड। |
|
|  | [getRotationAngle()](#getRotationAngle--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)। |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)। |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण। |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण। |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण। |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण। |
|
|  | [getMargin()](#getMargin--) | हस्ताक्षर और दस्तावेज़ किनारों के बीच की दूरी को प्राप्त करता है या सेट करता है। |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | हस्ताक्षर और दस्तावेज़ किनारों के बीच की दूरी को प्राप्त करता है या सेट करता है। |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) को प्राप्त करता है या सेट करता है। |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) को प्राप्त करता है या सेट करता है। |
|
|  | [getTransparency()](#getTransparency--) | हस्ताक्षर की पारदर्शिता (0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक का मान) को प्राप्त करता है या सेट करता है। |
|
|  | [setTransparency(double value)](#setTransparency-double-) | हस्ताक्षर की पारदर्शिता (0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक का मान) को प्राप्त करता है या सेट करता है। |
|
|  | [getText()](#getText--) | हस्ताक्षर का टेक्स्ट प्राप्त करता है या सेट करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | हस्ताक्षर का टेक्स्ट प्राप्त करता है या सेट करता है। |
|
|  | [getFont()](#getFont--) | हस्ताक्षर का फ़ॉन्ट प्राप्त करता है या सेट करता है। |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | हस्ताक्षर का फ़ॉन्ट प्राप्त करता है या सेट करता है। |
|
|  | [getForeColor()](#getForeColor--) | हस्ताक्षर का अग्र रंग प्राप्त करता है या सेट करता है। |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | हस्ताक्षर का अग्र रंग प्राप्त करता है या सेट करता है। |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | टेक्स्ट हस्ताक्षर कार्यान्वयन का प्रकार प्राप्त करता है या सेट करता है। |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | टेक्स्ट हस्ताक्षर कार्यान्वयन का प्रकार प्राप्त करता है या सेट करता है। |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | हस्ताक्षर के भीतर टेक्स्ट का क्षैतिज संरेखण। |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | हस्ताक्षर के भीतर टेक्स्ट का क्षैतिज संरेखण। |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | हस्ताक्षर के भीतर टेक्स्ट का लंबवत संरेखण। |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | हस्ताक्षर के भीतर टेक्स्ट का लंबवत संरेखण। |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | टेक्स्ट फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है जिसमें टेक्स्ट हस्ताक्षर रखा जाता है। |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | टेक्स्ट फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है जिसमें टेक्स्ट हस्ताक्षर रखा जाता है। |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | टेक्स्ट हस्ताक्षर रखने के लिए फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है या सेट करता है। |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | टेक्स्ट हस्ताक्षर रखने के लिए फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है या सेट करता है। |
|
|  | [getShapeType()](#getShapeType--) | टेक्स्ट रखने के लिए आकार का प्रकार प्राप्त करता है या सेट करता है। |
|
|  | [setShapeType(int value)](#setShapeType-int-) | टेक्स्ट रखने के लिए आकार का प्रकार प्राप्त करता है या सेट करता है। |
|
|  | [getSignatureID()](#getSignatureID--) | हस्ताक्षर की अद्वितीय आईडी प्राप्त करता है या सेट करता है। |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | हस्ताक्षर की अद्वितीय आईडी प्राप्त करता है या सेट करता है। |
|
|  | [getBorder()](#getBorder--) | सीमा सेटिंग्स निर्दिष्ट करें |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | सीमा सेटिंग्स निर्दिष्ट करें |
|
|  | [getBackground()](#getBackground--) | हस्ताक्षर पृष्ठभूमि सेटिंग्स प्राप्त करता है या सेट करता है। |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | हस्ताक्षर पृष्ठभूमि सेटिंग्स प्राप्त करता है या सेट करता है। |
|
|  | [getNative()](#getNative--) | स्थानीय गुण प्राप्त करता है या सेट करता है। |
|
|  | [setNative(boolean value)](#setNative-boolean-) | स्थानीय गुण प्राप्त करता है या सेट करता है। |
|
|  | [getShapePosition()](#getShapePosition--) | परिभाषित करता है कि आकार दस्तावेज़ लेआउट में कहाँ प्रस्तुत किया जाना चाहिए |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | परिभाषित करता है कि आकार दस्तावेज़ लेआउट में कहाँ प्रस्तुत किया जाना चाहिए |
|
|  | [validate()](#validate--) | विकल्प पैरामीटरों को मान्य करने के लिए आंतरिक विधि। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


डिफ़ॉल्ट वैल्यूज़ के साथ SignTextOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


टेक्स्ट के साथ SignTextOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | हस्ताक्षर टेक्स्ट। |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाएँ X स्थिति माप मानों में
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType प्रॉपर्टी)।
(यदि क्षैतिज संरेखण निर्दिष्ट नहीं है तो काम करता है)।


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाएँ X स्थिति माप मानों में
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType प्रॉपर्टी)।
(यदि क्षैतिज संरेखण निर्दिष्ट नहीं है तो काम करता है)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति माप मानों में
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType प्रॉपर्टी)।
(यदि लंबवत संरेखण निर्दिष्ट नहीं है तो काम करता है)।


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति माप मानों में
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType प्रॉपर्टी)।
(यदि लंबवत संरेखण निर्दिष्ट नहीं है तो काम करता है)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई माप मानों में
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType प्रॉपर्टी).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की चौड़ाई माप मानों में
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType प्रॉपर्टी).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की ऊँचाई माप मानों में
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType प्रॉपर्टी).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की ऊँचाई माप मानों में
(पिक्सेल, प्रतिशत या मिलीमीटर देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType प्रॉपर्टी).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


बाएँ और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)।


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


बाएँ और शीर्ष गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


चौड़ाई और ऊँचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)।


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


चौड़ाई और ऊँचाई गुणों के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


दस्तावेज़ पृष्ठ पर स्ट्रेच मोड।


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


दस्तावेज़ पृष्ठ पर स्ट्रेच मोड।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)।


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण।


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण।


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


हस्ताक्षर और दस्तावेज़ किनारों के बीच की दूरी को प्राप्त करता है या सेट करता है।
(केवल तभी काम करता है जब क्षैतिज या लंबवत संरेखण निर्दिष्ट हो)।


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


हस्ताक्षर और दस्तावेज़ किनारों के बीच की दूरी को प्राप्त करता है या सेट करता है।
(केवल तभी काम करता है जब क्षैतिज या लंबवत संरेखण निर्दिष्ट हो)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) को प्राप्त करता है या सेट करता है।


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


हस्ताक्षर की पारदर्शिता प्राप्त करता है या सेट करता है (मान 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक)। डिफ़ॉल्ट मान 0 (अपारदर्शी) है।


**Returns:**
डबल
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


हस्ताक्षर की पारदर्शिता प्राप्त करता है या सेट करता है (मान 0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक)। डिफ़ॉल्ट मान 0 (अपारदर्शी) है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getText() {#getText--}
```
public final String getText()
```


हस्ताक्षर का टेक्स्ट प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


हस्ताक्षर का टेक्स्ट प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


हस्ताक्षर का फ़ॉन्ट प्राप्त करता है या सेट करता है।


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


हस्ताक्षर का फ़ॉन्ट प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


हस्ताक्षर का अग्र रंग प्राप्त करता है या सेट करता है।


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


हस्ताक्षर का अग्र रंग प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


टेक्स्ट हस्ताक्षर कार्यान्वयन का प्रकार प्राप्त करता है या सेट करता है।


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


टेक्स्ट हस्ताक्षर कार्यान्वयन का प्रकार प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


हस्ताक्षर के भीतर टेक्स्ट का क्षैतिज संरेखण।
यह सुविधा केवल इमेज और एनोटेशन हस्ताक्षर कार्यान्वयनों के लिए समर्थित है
(देखें [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation प्रॉपर्टी)।


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


हस्ताक्षर के भीतर टेक्स्ट का क्षैतिज संरेखण।
यह सुविधा केवल इमेज और एनोटेशन हस्ताक्षर कार्यान्वयनों के लिए समर्थित है
(देखें [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation प्रॉपर्टी)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


हस्ताक्षर के भीतर टेक्स्ट का लंबवत संरेखण।
यह सुविधा केवल इमेज हस्ताक्षर कार्यान्वयन के लिए समर्थित है
(देखें [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation प्रॉपर्टी)।


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


हस्ताक्षर के भीतर टेक्स्ट का लंबवत संरेखण।
यह सुविधा केवल इमेज हस्ताक्षर कार्यान्वयन के लिए समर्थित है
(देखें [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation प्रॉपर्टी)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


टेक्स्ट फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है जिसमें टेक्स्ट हस्ताक्षर रखा जाता है।
यह प्रॉपर्टी केवल SignatureImplementation = TextToFormField के साथ उपयोग की जा सकती है।


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


टेक्स्ट फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है जिसमें टेक्स्ट हस्ताक्षर रखा जाता है।
यह प्रॉपर्टी केवल SignatureImplementation = TextToFormField के साथ उपयोग की जा सकती है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


टेक्स्ट हस्ताक्षर रखने के लिए फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है या सेट करता है।
यह प्रॉपर्टी केवल SignatureImplementation = TextToFormField के साथ उपयोग की जा सकती है।
डिफ़ॉल्ट मान AllTextTypes है।


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


टेक्स्ट हस्ताक्षर रखने के लिए फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है या सेट करता है।
यह प्रॉपर्टी केवल SignatureImplementation = TextToFormField के साथ उपयोग की जा सकती है।
डिफ़ॉल्ट मान AllTextTypes है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


टेक्स्ट रखने के लिए आकार का प्रकार प्राप्त करता है या सेट करता है।
यह प्रॉपर्टी केवल SignatureImplementation = TextStamp के साथ उपयोग की जा सकती है।
डिफ़ॉल्ट मान Rectangle है।


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


टेक्स्ट रखने के लिए आकार का प्रकार प्राप्त करता है या सेट करता है।
यह प्रॉपर्टी केवल SignatureImplementation = TextStamp के साथ उपयोग की जा सकती है।
डिफ़ॉल्ट मान Rectangle है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


हस्ताक्षर की अद्वितीय आईडी प्राप्त करता है या सेट करता है। इसे हस्ताक्षर सत्यापन विकल्पों में उपयोग किया जा सकता है। यह प्रॉपर्टी केवल PDF दस्तावेज़ों के लिए समर्थित है


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


हस्ताक्षर की अद्वितीय आईडी प्राप्त करता है या सेट करता है। इसे हस्ताक्षर सत्यापन विकल्पों में उपयोग किया जा सकता है। यह प्रॉपर्टी केवल PDF दस्तावेज़ों के लिए समर्थित है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


सीमा सेटिंग्स निर्दिष्ट करें


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


सीमा सेटिंग्स निर्दिष्ट करें


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


हस्ताक्षर पृष्ठभूमि सेटिंग्स प्राप्त करता है या सेट करता है।


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


हस्ताक्षर पृष्ठभूमि सेटिंग्स प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


स्थानीय गुण प्राप्त करता है या सेट करता है। यदि इसे सेट किया जाता है तो दस्तावेज़-विशिष्ट हस्ताक्षर उपयोग किए जा सकते हैं।
वर्ड प्रोसेसिंग दस्तावेज़ों के लिए स्थानीय टेक्स्ट वॉटरमार्क सामान्य से अलग है, उदाहरण के लिए।


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


स्थानीय गुण प्राप्त करता है या सेट करता है। यदि इसे सेट किया जाता है तो दस्तावेज़-विशिष्ट हस्ताक्षर उपयोग किए जा सकते हैं।
वर्ड प्रोसेसिंग दस्तावेज़ों के लिए स्थानीय टेक्स्ट वॉटरमार्क सामान्य से अलग है, उदाहरण के लिए।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


परिभाषित करता है कि आकार दस्तावेज़ लेआउट में कहाँ प्रस्तुत किया जाना चाहिए


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


परिभाषित करता है कि आकार दस्तावेज़ लेआउट में कहाँ प्रस्तुत किया जाना चाहिए


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### validate() {#validate--}
```
public void validate()
```


विकल्प पैरामीटरों को मान्य करने के लिए आंतरिक विधि।


### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
