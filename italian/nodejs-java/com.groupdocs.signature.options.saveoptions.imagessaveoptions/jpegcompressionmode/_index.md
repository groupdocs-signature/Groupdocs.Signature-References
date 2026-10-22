---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Specifica le modalità di compressione JPEG."
type: docs
weight: 17
url: /it/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Specifica le modalità di compressione JPEG.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Baseline](#Baseline) | La compressione di base. |
| [Progressive](#Progressive) | La compressione progressiva. |
| [Lossless](#Lossless) | La compressione senza perdita. |
| [JpegLs](#JpegLs) | La compressione JPEG-LS. |
### Baseline {#Baseline}
```
public static final int Baseline
```


La compressione di base.

### Progressive {#Progressive}
```
public static final int Progressive
```


La compressione progressiva.

### Lossless {#Lossless}
```
public static final int Lossless
```


La compressione senza perdita. Usa questo tipo di compressione con attenzione perché molti visualizzatori di immagini non lo supportano. Se lo usi, prova ad assegnare la proprietà JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) ai valori [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) o [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Rgb).

### JpegLs {#JpegLs}
```
public static final int JpegLs
```


La compressione JPEG-LS. Usa questo tipo di compressione con attenzione perché molti visualizzatori di immagini non lo supportano. Se lo usi, prova ad assegnare la proprietà JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) al valore [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale).

