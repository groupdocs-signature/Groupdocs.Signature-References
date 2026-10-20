---
title: "JpegSaveOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Jpeg-sparalternativ för bilddokument."
type: docs
weight: 19
url: /sv/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Jpeg-sparalternativ för bilddokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | Skapar JpegSaveOptions med standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | Hämtar eller anger bitar per kanal för förlustfri JPEG-bild. |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Hämtar eller anger bitar per kanal för förlustfri JPEG-bild. |
|
|  | [getColorType()](#getColorType--) | Hämtar eller anger färgtypen för JPEG-bild. |
|
|  | [setColorType(int value)](#setColorType-int-) | Hämtar eller anger färgtypen för JPEG-bild. |
|
|  | [getComment()](#getComment--) | Hämtar eller anger JPEG-filens kommentar. |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | Hämtar eller anger JPEG-filens kommentar. |
|
|  | [getCompressionType()](#getCompressionType--) | Hämtar eller anger komprimeringstypen. |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | Hämtar eller anger komprimeringstypen. |
|
|  | [getQuality()](#getQuality--) | Hämtar eller anger bildkvaliteten. |
|
|  | [setQuality(int value)](#setQuality-int-) | Hämtar eller anger bildkvaliteten. |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | Hämtar eller anger provrundningsläget för att anpassa ett 8-bitars värde till ett n-bitars värde |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Hämtar eller anger provrundningsläget för att anpassa ett 8-bitars värde till ett n-bitars värde |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | Hämtar eller anger filformat för signerat dokument. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Hämtar eller anger filformat för signerat dokument. |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Skapar JpegSaveOptions med standardvärden.


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Hämtar eller anger bitar per kanal för förlustfri JPEG-bild.
Nu stöder vi från 2 till 8 bitar per kanal.


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Hämtar eller anger bitar per kanal för förlustfri JPEG-bild.
Nu stöder vi från 2 till 8 bitar per kanal.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Hämtar eller anger färgtypen för JPEG-bild.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Hämtar eller anger färgtypen för JPEG-bild.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Hämtar eller anger JPEG-filens kommentar.


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Hämtar eller anger JPEG-filens kommentar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Hämtar eller anger komprimeringstypen.


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Hämtar eller anger komprimeringstypen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Hämtar eller anger bildkvaliteten.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Hämtar eller anger bildkvaliteten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Hämtar eller anger provrundningsläget för att anpassa ett 8-bitars värde till ett n-bitars värde
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Hämtar eller anger provrundningsläget för att anpassa ett 8-bitars värde till ett n-bitars värde
JpegOptions.BitsPerChannel.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Hämtar eller anger filformat för signerat dokument. Dold eftersom den inte används för den här alternativklassen.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Hämtar eller anger filformat för signerat dokument. Dold eftersom den inte används för den här alternativklassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

