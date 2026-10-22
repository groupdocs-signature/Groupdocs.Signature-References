---
title: "GifSaveOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "इमेज दस्तावेज़ों के लिए GIF फॉर्मेट सेव विकल्प।"
type: docs
weight: 15
url: /hi/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

इमेज दस्तावेज़ों के लिए GIF फॉर्मेट सेव विकल्प।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [GifSaveOptions()](#GifSaveOptions--) | डिफ़ॉल्ट मानों के साथ GifSaveOptions बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | GIF पृष्ठभूमि रंग सूचकांक को प्राप्त करता है या सेट करता है। |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | GIF पृष्ठभूमि रंग सूचकांक को प्राप्त करता है या सेट करता है। |
| [getColorResolution()](#getColorResolution--) | GIF रंग रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| [setColorResolution(byte value)](#setColorResolution-byte-) | GIF रंग रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [hasTrailer()](#hasTrailer--) | GIF में ट्रेलर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setTrailer(boolean value)](#setTrailer-boolean-) | GIF में ट्रेलर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getInterlaced()](#getInterlaced--) | यदि छवि को इंटरलेस किया जाना चाहिए तो सत्य। |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | यदि छवि को इंटरलेस किया जाना चाहिए तो सत्य। |
| [isPaletteSorted()](#isPaletteSorted--) | पैलेट प्रविष्टियों को क्रमबद्ध किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | पैलेट प्रविष्टियों को क्रमबद्ध किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | GIF पिक्सेल अनुपात को प्राप्त करता है या सेट करता है। |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | GIF पिक्सेल अनुपात को प्राप्त करता है या सेट करता है। |
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


डिफ़ॉल्ट मानों के साथ GifSaveOptions बनाता है।

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


GIF पृष्ठभूमि रंग सूचकांक को प्राप्त करता है या सेट करता है।

**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


GIF पृष्ठभूमि रंग सूचकांक को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


GIF रंग रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है।

--------------------

Color Resolution - मूल छवि में उपलब्ध प्रत्येक प्राथमिक रंग के बिट्स की संख्या, माइनस 1। यह मान ग्राफिक में चयनित रंगों के पूरे पैलेट का आकार दर्शाता है, न कि ग्राफिक में वास्तव में उपयोग किए गए रंगों की संख्या। उदाहरण के लिए, यदि इस फ़ील्ड में मान 3 है, तो मूल छवि के पैलेट में प्रत्येक प्राथमिक रंग के लिए 4 बिट्स उपलब्ध थे जो छवि बनाने के लिए उपयोग किए गए। इस मान को मूल पैलेट की समृद्धि को दर्शाने के लिए सेट किया जाना चाहिए, भले ही स्रोत मशीन पर पूरे पैलेट के सभी रंग उपलब्ध न हों।

**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


GIF रंग रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है।

--------------------

Color Resolution - मूल छवि में उपलब्ध प्रत्येक प्राथमिक रंग के बिट्स की संख्या, माइनस 1। यह मान ग्राफिक में चयनित रंगों के पूरे पैलेट का आकार दर्शाता है, न कि ग्राफिक में वास्तव में उपयोग किए गए रंगों की संख्या। उदाहरण के लिए, यदि इस फ़ील्ड में मान 3 है, तो मूल छवि के पैलेट में प्रत्येक प्राथमिक रंग के लिए 4 बिट्स उपलब्ध थे जो छवि बनाने के लिए उपयोग किए गए। इस मान को मूल पैलेट की समृद्धि को दर्शाने के लिए सेट किया जाना चाहिए, भले ही स्रोत मशीन पर पूरे पैलेट के सभी रंग उपलब्ध न हों।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

--------------------

पैलेट सुधार का अर्थ है कि जब भी छवि को GIF में निर्यात किया जाता है, स्रोत छवि के रंगों का विश्लेषण किया जाता है ताकि सबसे उपयुक्त पैलेट बनाया जा सके (यदि छवि का पैलेट मौजूद नहीं है या विकल्पों में निर्दिष्ट नहीं है)। विश्लेषण प्रक्रिया में कुछ समय लगता है, लेकिन आउटपुट छवि में सबसे उपयुक्त रंग पैलेट होगा और परिणाम दृश्य रूप से बेहतर होगा।

**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

--------------------

पैलेट सुधार का अर्थ है कि जब भी छवि को GIF में निर्यात किया जाता है, स्रोत छवि के रंगों का विश्लेषण किया जाता है ताकि सबसे उपयुक्त पैलेट बनाया जा सके (यदि छवि का पैलेट मौजूद नहीं है या विकल्पों में निर्दिष्ट नहीं है)। विश्लेषण प्रक्रिया में कुछ समय लगता है, लेकिन आउटपुट छवि में सबसे उपयुक्त रंग पैलेट होगा और परिणाम दृश्य रूप से बेहतर होगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


GIF में ट्रेलर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


GIF में ट्रेलर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


यदि छवि को इंटरलेस किया जाना चाहिए तो सत्य।

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


यदि छवि को इंटरलेस किया जाना चाहिए तो सत्य।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


पैलेट प्रविष्टियों को क्रमबद्ध किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


पैलेट प्रविष्टियों को क्रमबद्ध किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


GIF पिक्सेल अनुपात को प्राप्त करता है या सेट करता है।

--------------------

Pixel Aspect Ratio - मूल छवि में पिक्सेल के अनुपात का अनुमान लगाने के लिए उपयोग किया जाने वाला कारक। यदि फ़ील्ड का मान 0 नहीं है, तो इस अनुपात का अनुमान निम्न सूत्र के आधार पर किया जाता है: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64। पिक्सेल अनुपात को पिक्सेल की चौड़ाई को उसकी ऊँचाई से विभाजित करने के रूप में परिभाषित किया गया है। इस फ़ील्ड में मान की सीमा 4:1 (सबसे चौड़ा पिक्सेल) से 1:4 (सबसे ऊँचा पिक्सेल) तक 1/64 के चरण में निर्दिष्ट की जा सकती है। मान: 0 - कोई अनुपात जानकारी नहीं दी गई है। 1..255 - गणना में उपयोग किया गया मान।

**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


GIF पिक्सेल अनुपात को प्राप्त करता है या सेट करता है।

--------------------

Pixel Aspect Ratio - मूल छवि में पिक्सेल के अनुपात का अनुमान लगाने के लिए उपयोग किया जाने वाला कारक। यदि फ़ील्ड का मान 0 नहीं है, तो इस अनुपात का अनुमान निम्न सूत्र के आधार पर किया जाता है: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64। पिक्सेल अनुपात को पिक्सेल की चौड़ाई को उसकी ऊँचाई से विभाजित करने के रूप में परिभाषित किया गया है। इस फ़ील्ड में मान की सीमा 4:1 (सबसे चौड़ा पिक्सेल) से 1:4 (सबसे ऊँचा पिक्सेल) तक 1/64 के चरण में निर्दिष्ट की जा सकती है। मान: 0 - कोई अनुपात जानकारी नहीं दी गई है। 1..255 - गणना में उपयोग किया गया मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

