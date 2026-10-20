---
title: "QrCodeSearchOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "QR-Kod imzaları için soyut arama seçeneklerini temsil eder."
type: docs
weight: 16
url: /tr/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

QR-Kod imzaları için soyut arama seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | QRCodeSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QRCodeSearchOptions sınıfının yeni bir örneğini kodlama türü değeriyle başlatır. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | QRCodeSearchOptions sınıfının yeni bir örneğini kodlama türü ve metin değerleriyle başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QR-Codes aramak için Encode Type özelliğini belirtir. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR-Codes aramak için Encode Type özelliğini belirtir. |
|
|  | [getText()](#getText--) | Aranıp eşleşmesi gerekiyorsa QR-Code İmza Metnini belirtir. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Aranıp eşleşmesi gerekiyorsa QR-Code İmza Metnini belirtir. |
|
|  | [getMatchType()](#getMatchType--) | QR-Code Metin Eşleşme Türü aramasını alır veya ayarlar. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | QR-Code Metin Eşleşme Türü aramasını alır veya ayarlar. |
|
|  | [getDataEncryption()](#getDataEncryption--) | QR-Code İmza Metni veya Veri özelliklerini kodlamak ve kodunu çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code İmza Metni veya Veri özelliklerini kodlamak ve kodunu çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
|
|  | [getReturnContent()](#getReturnContent--) | Belge sayfasındaki imzanın QR-Code görüntü içeriğini yakalama bayrağını alır veya ayarlar. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Belge sayfasındaki imzanın QR-Code görüntü içeriğini yakalama bayrağını alır veya ayarlar. |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent özelliği etkin olduğunda QR-Code imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent özelliği etkin olduğunda QR-Code imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


QRCodeSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


QRCodeSearchOptions sınıfının yeni bir örneğini kodlama türü değeriyle başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QR-Code kodlama türünü belirtir. |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


QRCodeSearchOptions sınıfının yeni bir örneğini kodlama türü ve metin değerleriyle başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QR-Code kodlama türünü belirtir. |
|
|  | metin | java.lang.String | QR-Code imzasının Metnini ayarla. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR-Codes aramak için Encode Type özelliğini belirtir.
Bu değer ayarlanmamışsa, arama desteklenen tüm QR-Code Türleri için işlenir.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QR-Codes aramak için Encode Type özelliğini belirtir.
Bu değer ayarlanmamışsa, arama desteklenen tüm QR-Code Türleri için işlenir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Aranıp eşleşmesi gerekiyorsa QR-Code İmza Metnini belirtir.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Aranıp eşleşmesi gerekiyorsa QR-Code İmza Metnini belirtir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


QR-Code Metin Eşleşme Türü aramasını alır veya ayarlar. Yalnızca Metin özelliği ayarlandığında kullanılır.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


QR-Code Metin Eşleşme Türü aramasını alır veya ayarlar. Yalnızca Metin özelliği ayarlandığında kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-Code İmza Metni veya Veri özelliklerini kodlamak ve kodunu çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-Code İmza Metni veya Veri özelliklerini kodlamak ve kodunu çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Belge sayfasındaki imzanın QR-Code görüntü içeriğini yakalama bayrağını alır veya ayarlar.
Bu bayrak true olarak ayarlanırsa, QR-Code imza görüntü içeriği gerekli formatta ham görüntü verisini korur.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Varsayılan olarak bu seçenek devre dışıdır.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Belge sayfasındaki imzanın QR-Code görüntü içeriğini yakalama bayrağını alır veya ayarlar.
Bu bayrak true olarak ayarlanırsa, QR-Code imza görüntü içeriği gerekli formatta ham görüntü verisini korur.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Varsayılan olarak bu seçenek devre dışıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


ReturnContent özelliği etkin olduğunda QR-Code imzasının döndürülen görüntü içeriğinin dosya türünü belirtir.
Varsayılan olarak Null olarak ayarlanır. Bu, QR-Code görüntü içeriğinin orijinal formatta döndürüleceği anlamına gelir.
Bu görüntü formatı şu konumda belirtilir
QrCodeSignature.Format
()
Olası desteklenen değerler: FileType.JPEG, FileType.PNG, FileType.BMP.
Sağlanan format desteklenmiyorsa, orijinal .png içindeki QR-Code görüntü içeriği döndürülecektir.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent özelliği etkin olduğunda QR-Code imzasının döndürülen görüntü içeriğinin dosya türünü belirtir.
Varsayılan olarak Null olarak ayarlanır. Bu, QR-Code görüntü içeriğinin orijinal formatta döndürüleceği anlamına gelir.
Bu görüntü formatı şu konumda belirtilir
QrCodeSignature.Format
()
Olası desteklenen değerler: FileType.JPEG, FileType.PNG, FileType.BMP.
Sağlanan format desteklenmiyorsa, orijinal .png içindeki QR-Code görüntü içeriği döndürülecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

