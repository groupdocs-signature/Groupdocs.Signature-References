---
title: JpegSaveOptions
second_title: GroupDocs.Signature for Java API Reference
description: Jpeg Save options for Image Documents.
type: docs
weight: 16
url: /java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Jpeg Save options for Image Documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegSaveOptions()](#JpegSaveOptions--) | Creates JpegSaveOptions with default values. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerChannel()](#getBitsPerChannel--) | Gets or sets bits per channel for lossless jpeg image. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Gets or sets bits per channel for lossless jpeg image. |
| [getColorType()](#getColorType--) | Gets or sets the color type for jpeg image. |
| [setColorType(int value)](#setColorType-int-) | Gets or sets the color type for jpeg image. |
| [getComment()](#getComment--) | Gets or sets the jpeg file comment. |
| [setComment(String value)](#setComment-java.lang.String-) | Gets or sets the jpeg file comment. |
| [getCompressionType()](#getCompressionType--) | Gets or sets the compression type. |
| [setCompressionType(int value)](#setCompressionType-int-) | Gets or sets the compression type. |
| [getQuality()](#getQuality--) | Gets or sets image quality. |
| [setQuality(int value)](#setQuality-int-) | Gets or sets image quality. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Gets or sets the sample rounding mode to fit an 8-bit value to an n-bit value JpegOptions.BitsPerChannel. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Gets or sets the sample rounding mode to fit an 8-bit value to an n-bit value JpegOptions.BitsPerChannel. |
| [getFileFormat()](#getFileFormat--) | Gets or sets file format of signed document. |
| [setFileFormat(int value)](#setFileFormat-int-) | Gets or sets file format of signed document. |
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Creates JpegSaveOptions with default values.

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Gets or sets bits per channel for lossless jpeg image. Now we support from 2 to 8 bits per channel.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Gets or sets bits per channel for lossless jpeg image. Now we support from 2 to 8 bits per channel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Gets or sets the color type for jpeg image.

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Gets or sets the color type for jpeg image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Gets or sets the jpeg file comment.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Gets or sets the jpeg file comment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Gets or sets the compression type.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Gets or sets the compression type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Gets or sets image quality.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Gets or sets image quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Gets or sets the sample rounding mode to fit an 8-bit value to an n-bit value JpegOptions.BitsPerChannel.

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Gets or sets the sample rounding mode to fit an 8-bit value to an n-bit value JpegOptions.BitsPerChannel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Gets or sets file format of signed document. Hidden because not in use for this options class.

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Gets or sets file format of signed document. Hidden because not in use for this options class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

