---
title: "TextureBrush"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "टेक्सचर ब्रश का प्रतिनिधित्व करता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

टेक्सचर ब्रश का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextureBrush()](#TextureBrush--) | डिफ़ॉल्ट मानों के साथ TextureBrush क्लास की नई इंस्टेंस को प्रारंभ करता है। |
| [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | इमेज फ़ाइल के साथ TextureBrush क्लास की नई इंस्टेंस को प्रारंभ करता है। |
| [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | इमेज स्ट्रीम विकल्प के साथ TextureBrush क्लास की नई इंस्टेंस को प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | टेक्सचर इमेज फ़ाइल पथ को प्राप्त करता है या सेट करता है। |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | टेक्सचर इमेज फ़ाइल पथ को प्राप्त करता है या सेट करता है। |
| [getImageStream()](#getImageStream--) | टेक्सचर इमेज स्ट्रीम को प्राप्त करता है या सेट करता है। |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | टेक्सचर इमेज स्ट्रीम को प्राप्त करता है या सेट करता है। |
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


डिफ़ॉल्ट मानों के साथ TextureBrush क्लास की नई इंस्टेंस को प्रारंभ करता है।

### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


इमेज फ़ाइल के साथ TextureBrush क्लास की नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageFilePath | java.lang.String | इमेज फ़ाइल पथ। |

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


इमेज स्ट्रीम विकल्प के साथ TextureBrush क्लास की नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageStream | java.io.InputStream | इमेज स्ट्रीम। |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


टेक्सचर इमेज फ़ाइल पथ को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ImageStream निर्दिष्ट नहीं किया गया हो।

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


टेक्सचर इमेज फ़ाइल पथ को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ImageStream निर्दिष्ट नहीं किया गया हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


टेक्सचर इमेज स्ट्रीम को प्राप्त करता है या सेट करता है। यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा ImageFilePath के बजाय उपयोग की जाती है।

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


टेक्सचर इमेज स्ट्रीम को प्राप्त करता है या सेट करता है। यदि यह प्रॉपर्टी निर्दिष्ट की गई है तो यह हमेशा ImageFilePath के बजाय उपयोग की जाती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.io.InputStream |  |

