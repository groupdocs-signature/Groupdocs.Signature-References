---
title: BarcodeSignOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents the Barcode signature options.
type: docs
weight: 10
url: /java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Represents the Barcode signature options.
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeSignOptions()](#BarcodeSignOptions--) | Initializes a new instance of the BarcodeSignOptions class with default values. |
| [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Initializes a new instance of the BarcodeSignOptions class with text. |
| [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initializes a new instance of the BarcodeSignOptions class with text. |
## Methods

| Method | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Gets or sets Barcode type. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Gets or sets Barcode type. |
| [getForeColor()](#getForeColor--) | Gets or sets the Fore color of Barcode bars Using of this property could cause problems with verification. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Gets or sets the Fore color of Barcode bars Using of this property could cause problems with verification. |
| [setForeColor(String value)](#setForeColor-java.lang.String-) | Gets or sets the Fore color of Barcode bars Using of this property could cause problems with verification. |
| [getInnerMargins()](#getInnerMargins--) | Gets or sets the space between Barcode elements and result image borders. |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Gets or sets the space between Barcode elements and result image borders. |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | Gets or sets the alignment of text in the result Barcode image. |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Gets or sets the alignment of text in the result Barcode image. |
| [getReturnContent()](#getReturnContent--) | Gets or sets flag to get Barcode image content of a signature which was put on document page. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Gets or sets flag to get Barcode image content of a signature which was put on document page. |
| [getReturnContentType()](#getReturnContentType--) | Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. |
| [validate()](#validate--) | Internal method to validate the Barcode options parameters. |
| [toString()](#toString--) | Override string conversion. |
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Initializes a new instance of the BarcodeSignOptions class with default values.

### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Initializes a new instance of the BarcodeSignOptions class with text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Barcode text |

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Initializes a new instance of the BarcodeSignOptions class with text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Barcode text |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode encode type see [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Gets or sets Barcode type.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Gets or sets Barcode type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Gets or sets the Fore color of Barcode bars Using of this property could cause problems with verification. Use it carefully.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Gets or sets the Fore color of Barcode bars Using of this property could cause problems with verification. Use it carefully.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Gets or sets the Fore color of Barcode bars Using of this property could cause problems with verification. Use it carefully.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Gets or sets the space between Barcode elements and result image borders.

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Gets or sets the space between Barcode elements and result image borders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Gets or sets the alignment of text in the result Barcode image. Default value is None.

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Gets or sets the alignment of text in the result Barcode image. Default value is None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Gets or sets flag to get Barcode image content of a signature which was put on document page. If this flag is set true, Barcode signature image content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Gets or sets flag to get Barcode image content of a signature which was put on document page. If this flag is set true, Barcode signature image content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. By default it set to Null. That means to return Barcode image content in original format. This image format is specified at  BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than Barcode image content in .png format will be returned.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specifies file type of returned image content of the Barcode signature when ReturnContent property is enabled. By default it set to Null. That means to return Barcode image content in original format. This image format is specified at  BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)) Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than Barcode image content in .png format will be returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Internal method to validate the Barcode options parameters.

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
