---
title: "JpegSaveOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "इमेज दस्तावेज़ों के लिए Jpeg सहेजने विकल्प।"
type: docs
weight: 19
url: /hi/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

इमेज दस्तावेज़ों के लिए Jpeg सहेजने विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | डिफ़ॉल्ट मानों के साथ JpegSaveOptions बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | प्राप्त या सेट करता है हानि‑रहित jpeg छवि के लिए प्रति चैनल बिट्स। |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | प्राप्त या सेट करता है हानि‑रहित jpeg छवि के लिए प्रति चैनल बिट्स। |
|
|  | [getColorType()](#getColorType--) | प्राप्त या सेट करता है jpeg छवि के लिए रंग प्रकार। |
|
|  | [setColorType(int value)](#setColorType-int-) | प्राप्त या सेट करता है jpeg छवि के लिए रंग प्रकार। |
|
|  | [getComment()](#getComment--) | प्राप्त या सेट करता है jpeg फ़ाइल टिप्पणी। |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | प्राप्त या सेट करता है jpeg फ़ाइल टिप्पणी। |
|
|  | [getCompressionType()](#getCompressionType--) | संपीड़न प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | संपीड़न प्रकार को प्राप्त करता है या सेट करता है। |
|
|  | [getQuality()](#getQuality--) | छवि गुणवत्ता को प्राप्त करता है या सेट करता है। |
|
|  | [setQuality(int value)](#setQuality-int-) | छवि गुणवत्ता को प्राप्त करता है या सेट करता है। |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | 8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड को प्राप्त करता है या सेट करता है। |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड को प्राप्त करता है या सेट करता है। |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


डिफ़ॉल्ट मानों के साथ JpegSaveOptions बनाता है।


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


प्राप्त या सेट करता है हानि‑रहित jpeg छवि के लिए प्रति चैनल बिट्स।
अब हम प्रत्येक चैनल के लिए 2 से 8 बिट्स का समर्थन करते हैं।


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


प्राप्त या सेट करता है हानि‑रहित jpeg छवि के लिए प्रति चैनल बिट्स।
अब हम प्रत्येक चैनल के लिए 2 से 8 बिट्स का समर्थन करते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


प्राप्त या सेट करता है jpeg छवि के लिए रंग प्रकार।


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


प्राप्त या सेट करता है jpeg छवि के लिए रंग प्रकार।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


प्राप्त या सेट करता है jpeg फ़ाइल टिप्पणी।


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


प्राप्त या सेट करता है jpeg फ़ाइल टिप्पणी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


संपीड़न प्रकार को प्राप्त करता है या सेट करता है।


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


संपीड़न प्रकार को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


छवि गुणवत्ता को प्राप्त करता है या सेट करता है।


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


छवि गुणवत्ता को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड को प्राप्त करता है या सेट करता है।
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड को प्राप्त करता है या सेट करता है।
JpegOptions.BitsPerChannel.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। यह विकल्प वर्ग के लिए उपयोग में न होने के कारण छिपा हुआ है।


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। यह विकल्प वर्ग के लिए उपयोग में न होने के कारण छिपा हुआ है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

