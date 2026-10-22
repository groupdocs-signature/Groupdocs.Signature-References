---
title: "JpegCompressionMode"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "JPEG संपीड़न मोड को निर्दिष्ट करता है।"
type: docs
weight: 17
url: /hi/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

JPEG संपीड़न मोड को निर्दिष्ट करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Baseline](#Baseline) | बेसलाइन संपीड़न। |
| [Progressive](#Progressive) | प्रोग्रेसिव संपीड़न। |
| [Lossless](#Lossless) | लॉसलेस संपीड़न। |
| [JpegLs](#JpegLs) | JPEG-LS संपीड़न। |
### Baseline {#Baseline}
```
public static final int Baseline
```


बेसलाइन संपीड़न।

### Progressive {#Progressive}
```
public static final int Progressive
```


प्रोग्रेसिव संपीड़न।

### Lossless {#Lossless}
```
public static final int Lossless
```


लॉसलेस संपीड़न। इस संपीड़न प्रकार का सावधानीपूर्वक उपयोग करें क्योंकि कई इमेज व्यूअर्स इसे समर्थन नहीं करते हैं। यदि आप इसका उपयोग करते हैं तो JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) प्रॉपर्टी को [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) या [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Rgb) मानों पर सेट करने का प्रयास करें।

### JpegLs {#JpegLs}
```
public static final int JpegLs
```


JPEG-LS संपीड़न। इस संपीड़न प्रकार का सावधानीपूर्वक उपयोग करें क्योंकि कई इमेज व्यूअर्स इसे समर्थन नहीं करते हैं। यदि आप इसका उपयोग करते हैं तो JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) प्रॉपर्टी को [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) मान पर सेट करने का प्रयास करें।

