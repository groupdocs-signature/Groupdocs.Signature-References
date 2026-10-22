---
title: "JpegSaveOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Options d’enregistrement JPEG pour les documents image."
type: docs
weight: 19
url: /fr/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Options d’enregistrement JPEG pour les documents image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [JpegSaveOptions()](#JpegSaveOptions--) | Crée des JpegSaveOptions avec les valeurs par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitsPerChannel()](#getBitsPerChannel--) | Obtient ou définit le nombre de bits par canal pour une image jpeg sans perte. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Obtient ou définit le nombre de bits par canal pour une image jpeg sans perte. |
| [getColorType()](#getColorType--) | Obtient ou définit le type de couleur pour l'image jpeg. |
| [setColorType(int value)](#setColorType-int-) | Obtient ou définit le type de couleur pour l'image jpeg. |
| [getComment()](#getComment--) | Obtient ou définit le commentaire du fichier jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | Obtient ou définit le commentaire du fichier jpeg. |
| [getCompressionType()](#getCompressionType--) | Obtient ou définit le type de compression. |
| [setCompressionType(int value)](#setCompressionType-int-) | Obtient ou définit le type de compression. |
| [getQuality()](#getQuality--) | Obtient ou définit la qualité de l'image. |
| [setQuality(int value)](#setQuality-int-) | Obtient ou définit la qualité de l'image. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Obtient ou définit le mode d'arrondi des échantillons pour adapter une valeur de 8 bits à une valeur de n bits JpegOptions.BitsPerChannel. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Obtient ou définit le mode d'arrondi des échantillons pour adapter une valeur de 8 bits à une valeur de n bits JpegOptions.BitsPerChannel. |
| [getFileFormat()](#getFileFormat--) | Obtient ou définit le format de fichier du document signé. |
| [setFileFormat(int value)](#setFileFormat-int-) | Obtient ou définit le format de fichier du document signé. |
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Crée des JpegSaveOptions avec les valeurs par défaut.

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Obtient ou définit le nombre de bits par canal pour une image jpeg sans perte. Nous supportons désormais de 2 à 8 bits par canal.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Obtient ou définit le nombre de bits par canal pour une image jpeg sans perte. Nous supportons désormais de 2 à 8 bits par canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtient ou définit le type de couleur pour l'image jpeg.

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Obtient ou définit le type de couleur pour l'image jpeg.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Obtient ou définit le commentaire du fichier jpeg.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Obtient ou définit le commentaire du fichier jpeg.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Obtient ou définit le type de compression.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Obtient ou définit le type de compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Obtient ou définit la qualité de l'image.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Obtient ou définit la qualité de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Obtient ou définit le mode d'arrondi des échantillons pour adapter une valeur de 8 bits à une valeur de n bits JpegOptions.BitsPerChannel.

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Obtient ou définit le mode d'arrondi des échantillons pour adapter une valeur de 8 bits à une valeur de n bits JpegOptions.BitsPerChannel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Obtient ou définit le format de fichier du document signé. Masqué car non utilisé pour cette classe d'options.

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Obtient ou définit le format de fichier du document signé. Masqué car non utilisé pour cette classe d'options.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

