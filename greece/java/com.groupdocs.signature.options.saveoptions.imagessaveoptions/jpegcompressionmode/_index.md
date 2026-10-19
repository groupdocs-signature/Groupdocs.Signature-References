---
title: "JpegCompressionMode"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Καθορίζει λειτουργίες συμπίεσης JPEG."
type: docs
weight: 17
url: /el/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Καθορίζει λειτουργίες συμπίεσης JPEG.

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Baseline](#Baseline) | Η βασική συμπίεση. |
|
|  | [Progressive](#Progressive) | Η προοδευτική συμπίεση. |
|
|  | [Lossless](#Lossless) | Η συμπίεση χωρίς απώλειες. |
|
|  | [JpegLs](#JpegLs) | Η συμπίεση JPEG-LS. |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


Η βασική συμπίεση.


### Progressive {#Progressive}
```
public static final int Progressive
```


Η προοδευτική συμπίεση.


### Lossless {#Lossless}
```
public static final int Lossless
```


Η συμπίεση χωρίς απώλειες. Χρησιμοποιήστε αυτόν τον τύπο συμπίεσης προσεκτικά επειδή
πολλοί προβολείς εικόνας δεν την υποστηρίζουν. Εάν τη χρησιμοποιήσετε, δοκιμάστε να ορίσετε το

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) ιδιότητα σε [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
ή [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb) τιμές.


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


Η συμπίεση JPEG-LS. Χρησιμοποιήστε αυτόν τον τύπο συμπίεσης προσεκτικά επειδή
πολλοί προβολείς εικόνας δεν την υποστηρίζουν. Εάν τη χρησιμοποιήσετε, δοκιμάστε να ορίσετε το

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) ιδιότητα σε [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
τιμή.


