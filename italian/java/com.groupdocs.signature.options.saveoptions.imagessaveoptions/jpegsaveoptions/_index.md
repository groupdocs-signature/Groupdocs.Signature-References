---
title: "JpegSaveOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Opzioni di salvataggio JPEG per documenti immagine."
type: docs
weight: 19
url: /it/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Opzioni di salvataggio JPEG per documenti immagine.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | Crea JpegSaveOptions con valori predefiniti. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | Ottiene o imposta i bit per canale per l'immagine jpeg senza perdita. |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Ottiene o imposta i bit per canale per l'immagine jpeg senza perdita. |
|
|  | [getColorType()](#getColorType--) | Ottiene o imposta il tipo di colore per l'immagine jpeg. |
|
|  | [setColorType(int value)](#setColorType-int-) | Ottiene o imposta il tipo di colore per l'immagine jpeg. |
|
|  | [getComment()](#getComment--) | Ottiene o imposta il commento del file jpeg. |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | Ottiene o imposta il commento del file jpeg. |
|
|  | [getCompressionType()](#getCompressionType--) | Ottiene o imposta il tipo di compressione. |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | Ottiene o imposta il tipo di compressione. |
|
|  | [getQuality()](#getQuality--) | Ottiene o imposta la qualità dell'immagine. |
|
|  | [setQuality(int value)](#setQuality-int-) | Ottiene o imposta la qualità dell'immagine. |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | Ottiene o imposta il formato file del documento firmato. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Ottiene o imposta il formato file del documento firmato. |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Crea JpegSaveOptions con valori predefiniti.


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Ottiene o imposta i bit per canale per l'immagine jpeg senza perdita.
Ora supportiamo da 2 a 8 bit per canale.


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Ottiene o imposta i bit per canale per l'immagine jpeg senza perdita.
Ora supportiamo da 2 a 8 bit per canale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Ottiene o imposta il tipo di colore per l'immagine jpeg.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Ottiene o imposta il tipo di colore per l'immagine jpeg.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Ottiene o imposta il commento del file jpeg.


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Ottiene o imposta il commento del file jpeg.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Ottiene o imposta il tipo di compressione.


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Ottiene o imposta il tipo di compressione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Ottiene o imposta la qualità dell'immagine.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Ottiene o imposta la qualità dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit
JpegOptions.BitsPerChannel.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Ottiene o imposta il formato file del documento firmato. Nascosto perché non è in uso per questa classe di opzioni.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Ottiene o imposta il formato file del documento firmato. Nascosto perché non è in uso per questa classe di opzioni.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

