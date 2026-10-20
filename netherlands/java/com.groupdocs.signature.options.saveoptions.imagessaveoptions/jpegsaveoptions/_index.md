---
title: "JpegSaveOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Jpeg-opslagopties voor afbeeldingsdocumenten."
type: docs
weight: 19
url: /nl/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Jpeg-opslagopties voor afbeeldingsdocumenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | Maakt JpegSaveOptions aan met standaardwaarden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | Haalt bits per kanaal op of stelt ze in voor verliesvrije jpeg-afbeelding. |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Haalt bits per kanaal op of stelt ze in voor verliesvrije jpeg-afbeelding. |
|
|  | [getColorType()](#getColorType--) | Haalt het kleurtype op of stelt het in voor jpeg-afbeelding. |
|
|  | [setColorType(int value)](#setColorType-int-) | Haalt het kleurtype op of stelt het in voor jpeg-afbeelding. |
|
|  | [getComment()](#getComment--) | Haalt het jpeg-bestandscommentaar op of stelt het in. |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | Haalt het jpeg-bestandscommentaar op of stelt het in. |
|
|  | [getCompressionType()](#getCompressionType--) | Haalt het compressietype op of stelt het in. |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | Haalt het compressietype op of stelt het in. |
|
|  | [getQuality()](#getQuality--) | Haalt de beeldkwaliteit op of stelt deze in. |
|
|  | [setQuality(int value)](#setQuality-int-) | Haalt de beeldkwaliteit op of stelt deze in. |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | Haalt de afrondingsmodus van het monster op of stelt deze in om een 8-bit waarde aan te passen aan een n-bit waarde. |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Haalt de afrondingsmodus van het monster op of stelt deze in om een 8-bit waarde aan te passen aan een n-bit waarde. |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | Haalt of stelt het bestandsformaat van het ondertekende document in. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Haalt of stelt het bestandsformaat van het ondertekende document in. |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Maakt JpegSaveOptions aan met standaardwaarden.


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Haalt bits per kanaal op of stelt ze in voor verliesvrije jpeg-afbeelding.
Nu ondersteunen we van 2 tot 8 bits per kanaal.


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Haalt bits per kanaal op of stelt ze in voor verliesvrije jpeg-afbeelding.
Nu ondersteunen we van 2 tot 8 bits per kanaal.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Haalt het kleurtype op of stelt het in voor jpeg-afbeelding.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Haalt het kleurtype op of stelt het in voor jpeg-afbeelding.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Haalt het jpeg-bestandscommentaar op of stelt het in.


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Haalt het jpeg-bestandscommentaar op of stelt het in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Haalt het compressietype op of stelt het in.


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Haalt het compressietype op of stelt het in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Haalt de beeldkwaliteit op of stelt deze in.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Haalt de beeldkwaliteit op of stelt deze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Haalt de afrondingsmodus van het monster op of stelt deze in om een 8-bit waarde aan te passen aan een n-bit waarde.
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Haalt de afrondingsmodus van het monster op of stelt deze in om een 8-bit waarde aan te passen aan een n-bit waarde.
JpegOptions.BitsPerChannel.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Haalt het bestandsformaat van het ondertekende document op of stelt het in. Verborgen omdat het niet wordt gebruikt voor deze optieklasse.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Haalt het bestandsformaat van het ondertekende document op of stelt het in. Verborgen omdat het niet wordt gebruikt voor deze optieklasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

