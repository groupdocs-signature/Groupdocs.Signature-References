---
title: "QrCodeSignOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "QR-Kod imza seçeneklerini temsil eder."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

QR-Kod imza seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [QrCodeSignOptions()](#QrCodeSignOptions--) | QRCodeSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | QRCodeSignOptions sınıfının yeni bir örneğini metinle başlatır. |
| [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | BarcodeSignOptions sınıfının yeni bir örneğini metinle başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | QRCode türünü alır veya ayarlar. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QRCode türünü alır veya ayarlar. |
| [getForeColor()](#getForeColor--) | QR-Code çubuklarının Fore rengini alır veya ayarlar. Bu özelliğin kullanılması doğrulama sırasında sorunlara neden olabilir. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | QR-Code çubuklarının Fore rengini alır veya ayarlar. Bu özelliğin kullanılması doğrulama sırasında sorunlara neden olabilir. |
| [setForeColor(String value)](#setForeColor-java.lang.String-) | QR-Code çubuklarının Fore rengini alır veya ayarlar. Bu özelliğin kullanılması doğrulama sırasında sorunlara neden olabilir. |
| [getInnerMargins()](#getInnerMargins--) | QRCode öğeleri ile sonuç görüntüsü kenarları arasındaki boşluğu alır veya ayarlar. |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | QRCode öğeleri ile sonuç görüntüsü kenarları arasındaki boşluğu alır veya ayarlar. |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | Sonuç QR-code görüntüsündeki metnin hizalamasını alır veya ayarlar. |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Sonuç QR-code görüntüsündeki metnin hizalamasını alır veya ayarlar. |
| [getLogoFilePath()](#getLogoFilePath--) | QR-code logo görüntüsü dosya adını alır veya ayarlar. |
| [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | QR-code logo görüntüsü dosya adını alır veya ayarlar. |
| [getLogoStream()](#getLogoStream--) | QR-code logo görüntüsü akışını alır veya ayarlar. |
| [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | QR-code logo görüntüsü akışını alır veya ayarlar. |
| [getData()](#getData--) | QR-Code içeriğine serileştirilecek özel nesneyi alır veya ayarlar. |
| [setData(Object value)](#setData-java.lang.Object-) | QR-Code içeriğine serileştirilecek özel nesneyi alır veya ayarlar. |
| [getDataEncryption()](#getDataEncryption--) | QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar. |
| [getReturnContent()](#getReturnContent--) | Belge sayfasına yerleştirilen bir imzanın QR-Kod görüntü içeriğini almak için bayrağı alır veya ayarlar. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Belge sayfasına yerleştirilen bir imzanın QR-Kod görüntü içeriğini almak için bayrağı alır veya ayarlar. |
| [getReturnContentType()](#getReturnContentType--) | ReturnContent özelliği etkin olduğunda QR-Kod imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent özelliği etkin olduğunda QR-Kod imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kılar. |
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


QRCodeSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


QRCodeSignOptions sınıfının yeni bir örneğini metinle başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | İmza metni. |

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


BarcodeSignOptions sınıfının yeni bir örneğini metinle başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | QRCode metni |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRCode kodlama türü bakınız [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QRCode türünü alır veya ayarlar.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QRCode türünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


QR-Kod çubuklarının ön renk değerini alır veya ayarlar. Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


QR-Kod çubuklarının ön renk değerini alır veya ayarlar. Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


QR-Kod çubuklarının ön renk değerini alır veya ayarlar. Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


QRCode öğeleri ile sonuç görüntüsü kenarları arasındaki boşluğu alır veya ayarlar.

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


QRCode öğeleri ile sonuç görüntüsü kenarları arasındaki boşluğu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Sonuç QR-kod görüntüsündeki metnin hizalamasını alır veya ayarlar. Varsayılan değer None'dur.

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Sonuç QR-kod görüntüsündeki metnin hizalamasını alır veya ayarlar. Varsayılan değer None'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


QR-kod logo görüntü dosya adını alır veya ayarlar. Bu özellik yalnızca LogoStream belirtilmediğinde kullanılır. Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.

**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


QR-kod logo görüntü dosya adını alır veya ayarlar. Bu özellik yalnızca LogoStream belirtilmediğinde kullanılır. Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


QR-kod logo görüntü akışını alır veya ayarlar. Bu özellik belirtilirse her zaman LogoGuid yerine kullanılır. Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.

**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


QR-kod logo görüntü akışını alır veya ayarlar. Bu özellik belirtilirse her zaman LogoGuid yerine kullanılır. Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


QR-Code içeriğine serileştirilecek özel nesneyi alır veya ayarlar.

**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


QR-Code içeriğine serileştirilecek özel nesneyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-Code İmza Metni veya Veri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulanmasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Belge sayfasına yerleştirilen bir imzanın QR-Kod görüntü içeriğini almak için bayrağı alır veya ayarlar. Bu bayrak true olarak ayarlanırsa, QR-Kod imza görüntü içeriği gereken formatta (ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType))) ham görüntü verisini korur. Varsayılan olarak bu seçenek devre dışıdır.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Belge sayfasına yerleştirilen bir imzanın QR-Kod görüntü içeriğini almak için bayrağı alır veya ayarlar. Bu bayrak true olarak ayarlanırsa, QR-Kod imza görüntü içeriği gereken formatta (ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType))) ham görüntü verisini korur. Varsayılan olarak bu seçenek devre dışıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


ReturnContent özelliği etkin olduğunda QR-Kod imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. Varsayılan olarak Null olarak ayarlanır. Bu, QR-Kod görüntü içeriğinin orijinal formatta döndürüleceği anlamına gelir. Bu görüntü formatı QrCodeSignature.Format'te belirtilir ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/\{@link QrCodeSignature\#(FileType)\}). Desteklenen olası değerler: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan format desteklenmiyorsa QR-Kod görüntü içeriği .png formatında döndürülür.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent özelliği etkin olduğunda QR-Kod imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. Varsayılan olarak Null olarak ayarlanır. Bu, QR-Kod görüntü içeriğinin orijinal formatta döndürüleceği anlamına gelir. Bu görüntü formatı QrCodeSignature.Format'te belirtilir ([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature\#getFormat)/\{@link QrCodeSignature\#(FileType)\}). Desteklenen olası değerler: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan format desteklenmiyorsa QR-Kod görüntü içeriği .png formatında döndürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
