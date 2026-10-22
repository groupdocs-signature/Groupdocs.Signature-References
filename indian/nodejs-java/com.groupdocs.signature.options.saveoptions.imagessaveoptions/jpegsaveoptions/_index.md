---
title: "JpegSaveOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "इमेज दस्तावेज़ों के लिए JPEG सेव विकल्प।"
type: docs
weight: 19
url: /hi/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

इमेज दस्तावेज़ों के लिए JPEG सेव विकल्प।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [JpegSaveOptions()](#JpegSaveOptions--) | डिफ़ॉल्ट मानों के साथ JpegSaveOptions बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBitsPerChannel()](#getBitsPerChannel--) | लॉसलेस jpeg छवि के लिए प्रति चैनल बिट्स को प्राप्त करता है या सेट करता है। |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | लॉसलेस jpeg छवि के लिए प्रति चैनल बिट्स को प्राप्त करता है या सेट करता है। |
| [getColorType()](#getColorType--) | jpeg छवि के लिए रंग प्रकार को प्राप्त करता है या सेट करता है। |
| [setColorType(int value)](#setColorType-int-) | jpeg छवि के लिए रंग प्रकार को प्राप्त करता है या सेट करता है। |
| [getComment()](#getComment--) | jpeg फ़ाइल टिप्पणी को प्राप्त करता है या सेट करता है। |
| [setComment(String value)](#setComment-java.lang.String-) | jpeg फ़ाइल टिप्पणी को प्राप्त करता है या सेट करता है। |
| [getCompressionType()](#getCompressionType--) | संपीड़न प्रकार को प्राप्त करता है या सेट करता है। |
| [setCompressionType(int value)](#setCompressionType-int-) | संपीड़न प्रकार को प्राप्त करता है या सेट करता है। |
| [getQuality()](#getQuality--) | छवि गुणवत्ता को प्राप्त करता है या सेट करता है। |
| [setQuality(int value)](#setQuality-int-) | छवि गुणवत्ता को प्राप्त करता है या सेट करता है। |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | 8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड को प्राप्त करता है या सेट करता है JpegOptions.BitsPerChannel। |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड को प्राप्त करता है या सेट करता है JpegOptions.BitsPerChannel। |
| [getFileFormat()](#getFileFormat--) | हस्ताक्षरित दस्तावेज़ का फ़ाइल फ़ॉर्मेट प्राप्त करता है या सेट करता है। |
| [setFileFormat(int value)](#setFileFormat-int-) | हस्ताक्षरित दस्तावेज़ का फ़ाइल फ़ॉर्मेट प्राप्त करता है या सेट करता है। |
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


डिफ़ॉल्ट मानों के साथ JpegSaveOptions बनाता है।

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


लॉसलेस jpeg छवि के लिए प्रति चैनल बिट्स को प्राप्त करता है या सेट करता है। अब हम 2 से 8 बिट्स प्रति चैनल का समर्थन करते हैं।

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


लॉसलेस jpeg छवि के लिए प्रति चैनल बिट्स को प्राप्त करता है या सेट करता है। अब हम 2 से 8 बिट्स प्रति चैनल का समर्थन करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


jpeg छवि के लिए रंग प्रकार को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


jpeg छवि के लिए रंग प्रकार को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


jpeg फ़ाइल टिप्पणी को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


jpeg फ़ाइल टिप्पणी को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड को प्राप्त करता है या सेट करता है JpegOptions.BitsPerChannel।

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड को प्राप्त करता है या सेट करता है JpegOptions.BitsPerChannel।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। इस विकल्प वर्ग के लिए उपयोग में न होने के कारण छिपा हुआ है।

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। इस विकल्प वर्ग के लिए उपयोग में न होने के कारण छिपा हुआ है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

