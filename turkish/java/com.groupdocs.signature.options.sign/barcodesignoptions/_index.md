---
title: "BarcodeSignOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Barkod imza seçeneklerini temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Barkod imza seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | BarcodeSignOptions sınıfının varsayılan değerlerle yeni bir örneğini başlatır. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | BarcodeSignOptions sınıfının metinle yeni bir örneğini başlatır. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | BarcodeSignOptions sınıfının metinle yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Barkod tipini alır veya ayarlar. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Barkod tipini alır veya ayarlar. |
|
|  | [getForeColor()](#getForeColor--) | Barkod çubuklarının Fore rengini alır veya ayarlar. |
Bu özelliğin kullanılması doğrulama sırasında sorunlara neden olabilir.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Barkod çubuklarının Fore rengini alır veya ayarlar. |
Bu özelliğin kullanılması doğrulama sırasında sorunlara neden olabilir.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Barkod çubuklarının Fore rengini alır veya ayarlar. |
Bu özelliğin kullanılması doğrulama sırasında sorunlara neden olabilir.
|
|  | [getInnerMargins()](#getInnerMargins--) | Barkod öğeleri ile sonuç görüntüsü kenarları arasındaki boşluğu alır veya ayarlar. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Barkod öğeleri ile sonuç görüntüsü kenarları arasındaki boşluğu alır veya ayarlar. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Sonuç Barcode görüntüsündeki metnin hizalamasını alır veya ayarlar. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Sonuç Barcode görüntüsündeki metnin hizalamasını alır veya ayarlar. |
|
|  | [getReturnContent()](#getReturnContent--) | Belge sayfasına yerleştirilen bir imzanın Barcode görüntü içeriğini almak için bayrağı alır veya ayarlar. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Belge sayfasına yerleştirilen bir imzanın Barcode görüntü içeriğini almak için bayrağı alır veya ayarlar. |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. |
|
|  | [validate()](#validate--) | Barcode seçenekleri parametrelerini doğrulamak için dahili yöntem. |
|
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


BarcodeSignOptions sınıfının varsayılan değerlerle yeni bir örneğini başlatır.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


BarcodeSignOptions sınıfının metinle yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Barcode metni |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


BarcodeSignOptions sınıfının metinle yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Barcode metni |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode kodlama türü için bakınız [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Barkod tipini alır veya ayarlar.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Barkod tipini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Barkod çubuklarının Fore rengini alır veya ayarlar.
Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Barkod çubuklarının Fore rengini alır veya ayarlar.
Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Barkod çubuklarının Fore rengini alır veya ayarlar.
Bu özelliğin kullanımı doğrulama sırasında sorunlara yol açabilir. Dikkatli kullanın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Barkod öğeleri ile sonuç görüntüsü kenarları arasındaki boşluğu alır veya ayarlar.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Barkod öğeleri ile sonuç görüntüsü kenarları arasındaki boşluğu alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Sonuç Barcode görüntüsündeki metnin hizalamasını alır veya ayarlar.
Varsayılan değer None'dur.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Sonuç Barcode görüntüsündeki metnin hizalamasını alır veya ayarlar.
Varsayılan değer None'dur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Belge sayfasına yerleştirilen bir imzanın Barcode görüntü içeriğini almak için bayrağı alır veya ayarlar.
Bu bayrak true olarak ayarlanırsa, Barcode imza görüntü içeriği gerekli formatta ham görüntü verisini koruyacaktır
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Varsayılan olarak bu seçenek devre dışıdır.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Belge sayfasına yerleştirilen bir imzanın Barcode görüntü içeriğini almak için bayrağı alır veya ayarlar.
Bu bayrak true olarak ayarlanırsa, Barcode imza görüntü içeriği gerekli formatta ham görüntü verisini koruyacaktır
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


ReturnContent özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türünü belirtir.
Varsayılan olarak Null olarak ayarlanır. Bu, Barcode görüntü içeriğinin özgün formatta döndürüleceği anlamına gelir.
Bu görüntü formatı şu konumda belirtilir
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Olası desteklenen değerler: FileType.JPEG, FileType.PNG, FileType.BMP.
Sağlanan format desteklenmiyorsa, Barcode görüntü içeriği .png formatında döndürülecektir.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türünü belirtir.
Varsayılan olarak Null olarak ayarlanır. Bu, Barcode görüntü içeriğinin özgün formatta döndürüleceği anlamına gelir.
Bu görüntü formatı şu konumda belirtilir
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
Olası desteklenen değerler: FileType.JPEG, FileType.PNG, FileType.BMP.
Sağlanan format desteklenmiyorsa, Barcode görüntü içeriği .png formatında döndürülecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Barcode seçenekleri parametrelerini doğrulamak için dahili yöntem.


### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl.


**Returns:**
java.lang.String -
