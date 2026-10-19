---
title: "JpegCompressionMode"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Spécifie les modes de compression JPEG."
type: docs
weight: 17
url: /fr/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
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
|  | [Baseline](#Baseline) | La compression de base. |
|
|  | [Progressive](#Progressive) | La compression progressive. |
|
|  | [Lossless](#Lossless) | La compression sans perte. |
|
|  | [JpegLs](#JpegLs) | La compression JPEG-LS. |
|
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


La compression sans perte. Utilisez ce type de compression avec prudence car
de nombreux visualiseurs d'images ne le prennent pas en charge. Si vous l'utilisez, essayez d'assigner le

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) propriété à [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
ou les valeurs [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb).


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


La compression JPEG-LS. Utilisez ce type de compression avec prudence car
de nombreux visualiseurs d'images ne le prennent pas en charge. Si vous l'utilisez, essayez d'assigner le

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) propriété à [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
valeur.


