---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Spécifie les modes de compression JPEG."
type: docs
weight: 17
url: /fr/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Spécifie les modes de compression JPEG.
## Champs

| Champ | Description |
| --- | --- |
| [Baseline](#Baseline) | La compression de base. |
| [Progressive](#Progressive) | La compression progressive. |
| [Lossless](#Lossless) | La compression sans perte. |
| [JpegLs](#JpegLs) | La compression JPEG-LS. |
### Baseline {#Baseline}
```
public static final int Baseline
```


La compression de base.

### Progressive {#Progressive}
```
public static final int Progressive
```


La compression progressive.

### Lossless {#Lossless}
```
public static final int Lossless
```


La compression sans perte. Utilisez ce type de compression avec précaution car de nombreux visionneurs d'images ne le prennent pas en charge. Si vous l'utilisez, essayez d'assigner la  JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) propriété aux valeurs [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) ou [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Rgb) valeurs.

### JpegLs {#JpegLs}
```
public static final int JpegLs
```


La compression JPEG-LS. Utilisez ce type de compression avec précaution car de nombreux visionneurs d'images ne le prennent pas en charge. Si vous l'utilisez, essayez d'assigner la  JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) propriété à la valeur [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale).

