---
title: "ImageSignOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "इमेज हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

इमेज हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ImageSignOptions()](#ImageSignOptions--) | डिफ़ॉल्ट मानों के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | इमेज फ़ाइल के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | इमेज स्ट्रीम के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | सिग्नेचर इमेज फ़ाइल पाथ को प्राप्त करता है या सेट करता है। |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | सिग्नेचर इमेज फ़ाइल पाथ को प्राप्त करता है या सेट करता है। |
| [getImageStream()](#getImageStream--) | सिग्नेचर इमेज स्ट्रीम को प्राप्त करता है या सेट करता है। |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | सिग्नेचर इमेज स्ट्रीम को प्राप्त करता है या सेट करता है। |
| [getLeft()](#getLeft--) | डॉक्यूमेंट पेज पर सिग्नेचर की बाएँ X स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में (देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType)। |
| [setLeft(int value)](#setLeft-int-) | डॉक्यूमेंट पेज पर सिग्नेचर की बाएँ X स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में (देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType)। |
| [getTop()](#getTop--) | डॉक्यूमेंट पेज पर सिग्नेचर की शीर्ष Y स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में (देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType)। |
| [setTop(int value)](#setTop-int-) | डॉक्यूमेंट पेज पर सिग्नेचर की शीर्ष Y स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में (देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType)। |
| [getWidth()](#getWidth--) | डॉक्यूमेंट पेज पर सिग्नेचर की चौड़ाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType। |
| [setWidth(int value)](#setWidth-int-) | डॉक्यूमेंट पेज पर सिग्नेचर की चौड़ाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType। |
| [getHeight()](#getHeight--) | डॉक्यूमेंट पेज पर सिग्नेचर की ऊँचाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में (देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType)। |
| [setHeight(int value)](#setHeight-int-) | डॉक्यूमेंट पेज पर सिग्नेचर की ऊँचाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में (देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType)। |
| [getLocationMeasureType()](#getLocationMeasureType--) | बाएँ और शीर्ष प्रॉपर्टीज़ के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | बाएँ और शीर्ष प्रॉपर्टीज़ के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [getSizeMeasureType()](#getSizeMeasureType--) | चौड़ाई और ऊँचाई प्रॉपर्टीज़ के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | चौड़ाई और ऊँचाई प्रॉपर्टीज़ के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)। |
| [getStretch()](#getStretch--) | दस्तावेज़ पृष्ठ पर स्ट्रेच मोड। |
| [setStretch(int value)](#setStretch-int-) | दस्तावेज़ पृष्ठ पर स्ट्रेच मोड। |
| [getRotationAngle()](#getRotationAngle--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)। |
| [setRotationAngle(int value)](#setRotationAngle-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का घूर्णन कोण (घड़ी की दिशा में)। |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण। |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का क्षैतिज संरेखण। |
| [getVerticalAlignment()](#getVerticalAlignment--) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण। |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | दस्तावेज़ पृष्ठ पर हस्ताक्षर का लंबवत संरेखण। |
| [getMargin()](#getMargin--) | हस्ताक्षर और दस्तावेज़ किनारों के बीच की दूरी प्राप्त करता है या सेट करता है। |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | हस्ताक्षर और दस्तावेज़ किनारों के बीच की दूरी प्राप्त करता है या सेट करता है। |
| [getMarginMeasureType()](#getMarginMeasureType--) | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) प्राप्त करता है या सेट करता है। |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) प्राप्त करता है या सेट करता है। |
| [getTransparency()](#getTransparency--) | हस्ताक्षर की पारदर्शिता (0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक) प्राप्त करता है या सेट करता है। |
| [setTransparency(double value)](#setTransparency-double-) | हस्ताक्षर की पारदर्शिता (0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक) प्राप्त करता है या सेट करता है। |
| [getShapePosition()](#getShapePosition--) | परिभाषित करता है कि दस्तावेज़ लेआउट में आकार कहाँ प्रस्तुत किया जाना चाहिए। |
| [setShapePosition(int value)](#setShapePosition-int-) | परिभाषित करता है कि दस्तावेज़ लेआउट में आकार कहाँ प्रस्तुत किया जाना चाहिए। |
| [getRectangle()](#getRectangle--) | दस्तावेज़ पर छवि रखने के लिए क्षेत्र का आयत। |
| [getBorder()](#getBorder--) | सीमा सेटिंग्स निर्दिष्ट करें। |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | सीमा सेटिंग्स निर्दिष्ट करें। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
| [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Base64 से पूर्वनिर्धारित छवि के साथ ImageSignOptions क्लास का नया उदाहरण बनाता है। |
| [dispose()](#dispose--) | आंतरिक संसाधनों को साफ़ करता है। |
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


डिफ़ॉल्ट मानों के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


इमेज फ़ाइल के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageFilePath | java.lang.String | छवि फ़ाइल पथ। |

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


इमेज स्ट्रीम के साथ ImageSignOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageStream | java.io.InputStream | छवि स्ट्रीम। |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


हस्ताक्षर छवि फ़ाइल पथ प्राप्त करता है या सेट करता है। यह गुण केवल तब उपयोग किया जाता है जब ImageStream निर्दिष्ट नहीं किया गया हो।

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


हस्ताक्षर छवि फ़ाइल पथ प्राप्त करता है या सेट करता है। यह गुण केवल तब उपयोग किया जाता है जब ImageStream निर्दिष्ट नहीं किया गया हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


हस्ताक्षर छवि स्ट्रीम प्राप्त करता है या सेट करता है। यदि यह गुण निर्दिष्ट किया गया है तो यह हमेशा ImageGuid के बजाय उपयोग किया जाता है।

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


हस्ताक्षर छवि स्ट्रीम प्राप्त करता है या सेट करता है। यदि यह गुण निर्दिष्ट किया गया है तो यह हमेशा ImageGuid के बजाय उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाएँ X स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType) में। (जब क्षैतिज संरेखण निर्दिष्ट नहीं हो तो काम करता है)।

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की बाएँ X स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType) में। (जब क्षैतिज संरेखण निर्दिष्ट नहीं हो तो काम करता है)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType) में। (जब लंबवत संरेखण निर्दिष्ट नहीं हो तो काम करता है)।

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


दस्तावेज़ पृष्ठ पर हस्ताक्षर की शीर्ष Y स्थिति माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर, देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType) में। (जब लंबवत संरेखण निर्दिष्ट नहीं हो तो काम करता है)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


डॉक्यूमेंट पेज पर सिग्नेचर की चौड़ाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType।

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


डॉक्यूमेंट पेज पर सिग्नेचर की चौड़ाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


डॉक्यूमेंट पेज पर सिग्नेचर की ऊँचाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में (देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType)।

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


डॉक्यूमेंट पेज पर सिग्नेचर की ऊँचाई माप मानों (पिक्सेल, प्रतिशत या मिलीमीटर) में (देखें [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


बाएँ और शीर्ष प्रॉपर्टीज़ के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)।

**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


बाएँ और शीर्ष प्रॉपर्टीज़ के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


चौड़ाई और ऊँचाई प्रॉपर्टीज़ के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)।

**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


चौड़ाई और ऊँचाई प्रॉपर्टीज़ के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


हस्ताक्षर और दस्तावेज़ किनारों के बीच की दूरी प्राप्त करता है या सेट करता है। (केवल तब काम करता है जब क्षैतिज या लंबवत संरेखण निर्दिष्ट हो)।

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


हस्ताक्षर और दस्तावेज़ किनारों के बीच की दूरी प्राप्त करता है या सेट करता है। (केवल तब काम करता है जब क्षैतिज या लंबवत संरेखण निर्दिष्ट हो)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) प्राप्त करता है या सेट करता है।

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


मार्जिन के लिए माप प्रकार (पिक्सेल, प्रतिशत या मिलीमीटर) प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


हस्ताक्षर की पारदर्शिता (0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक) प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 0 (अपारदर्शी) है।

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


हस्ताक्षर की पारदर्शिता (0.0 (अपारदर्शी) से 1.0 (स्पष्ट) तक) प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 0 (अपारदर्शी) है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


परिभाषित करता है कि दस्तावेज़ लेआउट में आकार कहाँ प्रस्तुत किया जाना चाहिए।

**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


परिभाषित करता है कि दस्तावेज़ लेआउट में आकार कहाँ प्रस्तुत किया जाना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


दस्तावेज़ पर छवि रखने के लिए क्षेत्र का आयत।

**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


सीमा सेटिंग्स निर्दिष्ट करें।

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


सीमा सेटिंग्स निर्दिष्ट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग रूपांतरण को ओवरराइड करें।

**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Base64 से पूर्वनिर्धारित छवि के साथ ImageSignOptions क्लास का नया उदाहरण बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| base64Content | java.lang.String | Base64 स्ट्रिंग फ़ॉर्मेट में छवि सामग्री। |

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


आंतरिक संसाधनों को साफ़ करता है।

