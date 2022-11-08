---
title: QrCodeSignOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents the QR-Code signature options.
type: docs
weight: 15
url: /java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Represents the QR-Code signature options.
## Constructors

| Constructor | Description |
| --- | --- |
| [QrCodeSignOptions()](#QrCodeSignOptions--) | Initializes a new instance of the QRCodeSignOptions class with default values. |
| [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Initializes a new instance of the QRCodeSignOptions class with text. |
| [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initializes a new instance of the BarcodeSignOptions class with text. |
## Methods

| Method | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Gets or sets QRCode type. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Gets or sets QRCode type. |
| [getForeColor()](#getForeColor--) | Gets or sets the Fore color of QR-Code bars Using of this property could cause problems with verification. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Gets or sets the Fore color of QR-Code bars Using of this property could cause problems with verification. |
| [getInnerMargins()](#getInnerMargins--) | Gets or sets the space between QRCode elements and result image borders. |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Gets or sets the space between QRCode elements and result image borders. |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | Gets or sets the alignment of text in the result QR-code image. |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Gets or sets the alignment of text in the result QR-code image. |
| [getLogoFilePath()](#getLogoFilePath--) | Gets or sets the QR-code logo image file name. |
| [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Gets or sets the QR-code logo image file name. |
| [getLogoStream()](#getLogoStream--) | Gets or sets the QR-code logo image stream. |
| [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Gets or sets the QR-code logo image stream. |
| [getData()](#getData--) | Gets or sets custom object to serialize to QR-Code content. |
| [setData(Object value)](#setData-java.lang.Object-) | Gets or sets custom object to serialize to QR-Code content. |
| [getDataEncryption()](#getDataEncryption--) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [getReturnContent()](#getReturnContent--) | Gets or sets flag to get QR-Code image content of a signature which was put on document page. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Gets or sets flag to get QR-Code image content of a signature which was put on document page. |
| [getReturnContentType()](#getReturnContentType--) | Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. |
| [toString()](#toString--) | Override string conversion. |
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Initializes a new instance of the QRCodeSignOptions class with default values.

### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Initializes a new instance of the QRCodeSignOptions class with text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Signature text. |

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Initializes a new instance of the BarcodeSignOptions class with text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | QRCode text |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRCode encode type see [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Gets or sets QRCode type.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Gets or sets QRCode type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Gets or sets the Fore color of QR-Code bars Using of this property could cause problems with verification. Use it carefully.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Gets or sets the Fore color of QR-Code bars Using of this property could cause problems with verification. Use it carefully.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Gets or sets the space between QRCode elements and result image borders.

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Gets or sets the space between QRCode elements and result image borders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Gets or sets the alignment of text in the result QR-code image. Default value is None.

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Gets or sets the alignment of text in the result QR-code image. Default value is None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Gets or sets the QR-code logo image file name. This property in use only if LogoStream is not specified. Using of this property could cause problems with verification. Use it carefully.

**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Gets or sets the QR-code logo image file name. This property in use only if LogoStream is not specified. Using of this property could cause problems with verification. Use it carefully.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Gets or sets the QR-code logo image stream. If this property is specified it is always used instead LogoGuid. Using of this property could cause problems with verification. Use it carefully.

**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Gets or sets the QR-code logo image stream. If this property is specified it is always used instead LogoGuid. Using of this property could cause problems with verification. Use it carefully.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Gets or sets custom object to serialize to QR-Code content.

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Gets or sets custom object to serialize to QR-Code content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Gets or sets flag to get QR-Code image content of a signature which was put on document page. If this flag is set true, QR-Code signature image content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Gets or sets flag to get QR-Code image content of a signature which was put on document page. If this flag is set true, QR-Code signature image content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. By default it set to Null. That means to return QR-Code image content in original format. This image format is specified at  QrCodeSignature.Format ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/[QrCodeSignature.setFormat(FileType)](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#setFormat-FileType-)) Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than QR-Code image content in .png format will be returned.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. By default it set to Null. That means to return QR-Code image content in original format. This image format is specified at  QrCodeSignature.Format ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/[QrCodeSignature.setFormat(FileType)](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#setFormat-FileType-)) Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than QR-Code image content in .png format will be returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
