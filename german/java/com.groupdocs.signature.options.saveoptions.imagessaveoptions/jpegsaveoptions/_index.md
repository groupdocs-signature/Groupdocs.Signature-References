---
title: "JpegSaveOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Jpeg-Speicheroptionen für Bilddokumente."
type: docs
weight: 19
url: /de/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Jpeg-Speicheroptionen für Bilddokumente.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | Erstellt JpegSaveOptions mit Standardwerten. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | Liest oder setzt Bits pro Kanal für verlustfreies jpeg-Bild. |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Liest oder setzt Bits pro Kanal für verlustfreies jpeg-Bild. |
|
|  | [getColorType()](#getColorType--) | Liest oder setzt den Farbtyp für jpeg-Bild. |
|
|  | [setColorType(int value)](#setColorType-int-) | Liest oder setzt den Farbtyp für jpeg-Bild. |
|
|  | [getComment()](#getComment--) | Liest oder setzt den jpeg-Dateikommentar. |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | Liest oder setzt den jpeg-Dateikommentar. |
|
|  | [getCompressionType()](#getCompressionType--) | Liest oder setzt den Kompressionstyp. |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | Liest oder setzt den Kompressionstyp. |
|
|  | [getQuality()](#getQuality--) | Liest oder setzt die Bildqualität. |
|
|  | [setQuality(int value)](#setQuality-int-) | Liest oder setzt die Bildqualität. |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | Liest oder setzt den Rundungsmodus der Stichprobe, um einen 8-Bit-Wert an einen n-Bit-Wert anzupassen |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Liest oder setzt den Rundungsmodus der Stichprobe, um einen 8-Bit-Wert an einen n-Bit-Wert anzupassen |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | Liest oder setzt das Dateiformat des signierten Dokuments. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Liest oder setzt das Dateiformat des signierten Dokuments. |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Erstellt JpegSaveOptions mit Standardwerten.


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Liest oder setzt Bits pro Kanal für verlustfreies jpeg-Bild.
Jetzt unterstützen wir von 2 bis 8 Bits pro Kanal.


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Liest oder setzt Bits pro Kanal für verlustfreies jpeg-Bild.
Jetzt unterstützen wir von 2 bis 8 Bits pro Kanal.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Liest oder setzt den Farbtyp für jpeg-Bild.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Liest oder setzt den Farbtyp für jpeg-Bild.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Liest oder setzt den jpeg-Dateikommentar.


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Liest oder setzt den jpeg-Dateikommentar.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Liest oder setzt den Kompressionstyp.


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Liest oder setzt den Kompressionstyp.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Liest oder setzt die Bildqualität.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Liest oder setzt die Bildqualität.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Liest oder setzt den Rundungsmodus der Stichprobe, um einen 8-Bit-Wert an einen n-Bit-Wert anzupassen
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Liest oder setzt den Rundungsmodus der Stichprobe, um einen 8-Bit-Wert an einen n-Bit-Wert anzupassen
JpegOptions.BitsPerChannel.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Liest oder setzt das Dateiformat des signierten Dokuments. Versteckt, weil es für diese Optionsklasse nicht verwendet wird.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Liest oder setzt das Dateiformat des signierten Dokuments. Versteckt, weil es für diese Optionsklasse nicht verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

