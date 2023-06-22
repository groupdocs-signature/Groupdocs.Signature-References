---
title: QrCodeSignature
second_title: GroupDocs.Signature for Java API Reference
description: Contains QR-code signature properties.
type: docs
weight: 16
url: /java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Contains QR-code signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Initialize QrCodeSignature object with signature identifier that was obtained after search process. |
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Specifies the QR-code Encode Type. |
| [getText()](#getText--) | Specifies text of QR-code. |
| [getFormat()](#getFormat--) | Specifies the format of QR-code signature image. |
| [getContent()](#getContent--) | Specifies QR-code binary data image content of type  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Obtain object from QR-Code Signature Text over deserialization. |
| [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Obtain object from QR-Code Signature Text over deserialization. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone QR-Code Signature instance. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Initialize QrCodeSignature object with signature identifier that was obtained after search process. This unique identifier is used to find additional properties for this signature from document signature information layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatureId | java.lang.String | Unique signature identifier obtained by sign or search method. |

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Specifies the QR-code Encode Type.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Specifies text of QR-code.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Specifies the format of QR-code signature image.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Specifies QR-code binary data image content of type  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). By default this property will not be set. Use property  QrCodeSearchOptions.ReturnContent ([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions\#setReturnContent-boolean-)) to enable this feature.

**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Obtain object from QR-Code Signature Text over deserialization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.Class<T> |  |

**Returns:**
T -  T : Type of object to deserialize from QR-Code Text
### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Obtain object from QR-Code Signature Text over deserialization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Set custom data encryption implementation

 T : Type of object to deserialize from QR-Code Text |
| type | java.lang.Class<T> |  |

**Returns:**
T - 
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overwrites Equals method to compare signature properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Signature object to compare with. |

**Returns:**
boolean - Returns true if passed signature object has same type and all its properties are equal to this instance properties.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Overrides GetHashCode method

**Returns:**
int - Signature hash code
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone QR-Code Signature instance.

**Returns:**
java.lang.Object - Returns cloned QR-code Signature instance.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| image | java.awt.image.BufferedImage |  |

