---
title: QrCodeSearchOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents abstract search Options for QR-Code signatures.
type: docs
weight: 15
url: /java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Represents abstract search Options for QR-Code signatures.
## Constructors

| Constructor | Description |
| --- | --- |
| [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Initializes a new instance of the QRCodeSearchOptions class with default values. |
| [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initializes a new instance of the QRCodeSearchOptions class with encode type value. |
| [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Initializes a new instance of the QRCodeSearchOptions class with encode type and text values. |
## Methods

| Method | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Specifies Encode Type property to search QR-Codes. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Specifies Encode Type property to search QR-Codes. |
| [getText()](#getText--) | Specifies QR-Code Signature Text if it should be searched and matched. |
| [setText(String value)](#setText-java.lang.String-) | Specifies QR-Code Signature Text if it should be searched and matched. |
| [getMatchType()](#getMatchType--) | Gets or sets QR-Code Text Match Type search. |
| [setMatchType(int value)](#setMatchType-int-) | Gets or sets QR-Code Text Match Type search. |
| [getDataEncryption()](#getDataEncryption--) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [getReturnContent()](#getReturnContent--) | Gets or sets flag to grab QR-Code image content of signature on document page. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Gets or sets flag to grab QR-Code image content of signature on document page. |
| [getReturnContentType()](#getReturnContentType--) | Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. |
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Initializes a new instance of the QRCodeSearchOptions class with default values.

### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Initializes a new instance of the QRCodeSearchOptions class with encode type value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Specifies QR-Code encode type. |

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Initializes a new instance of the QRCodeSearchOptions class with encode type and text values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Specifies QR-Code encode type. |
| text | java.lang.String | Set Text of QR-Code signature. |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Specifies Encode Type property to search QR-Codes. If this value is not set, search is processed for all supported QR-Code Types.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Specifies Encode Type property to search QR-Codes. If this value is not set, search is processed for all supported QR-Code Types.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Specifies QR-Code Signature Text if it should be searched and matched.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specifies QR-Code Signature Text if it should be searched and matched.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Gets or sets QR-Code Text Match Type search. It is used only when Text property is set.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Gets or sets QR-Code Text Match Type search. It is used only when Text property is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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


Gets or sets flag to grab QR-Code image content of signature on document page. If this flag is set true, QR-Code signature image content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Gets or sets flag to grab QR-Code image content of signature on document page. If this flag is set true, QR-Code signature image content will keep raw image data by required format  ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). By default this option is disabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. By default it set to Null. That means to return QR-Code image content in original format. This image format is specified at  QrCodeSignature.Format () Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than QR-Code image content in original .png will be returned.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specifies file type of returned image content of the QR-Code signature when ReturnContent property is enabled. By default it set to Null. That means to return QR-Code image content in original format. This image format is specified at  QrCodeSignature.Format () Possible supported values are: FileType.JPEG, FileType.PNG, FileType.BMP. If provided format is not supported than QR-Code image content in original .png will be returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

