---
title: "BarcodeSearchOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Barkod imzaları için soyut arama seçeneklerini temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Barkod imzaları için soyut arama seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | SearchBarcodeOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | SearchBarcodeOptions sınıfının yeni bir örneğini kodlama türü değeriyle başlatır. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | SearchBarcodeOptions sınıfının yeni bir örneğini kodlama türü ve metin değerleriyle başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Barkodları aramak için Kodlama Türü özelliğini belirtir. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Barkodları aramak için Kodlama Türü özelliğini belirtir. |
|
|  | [getText()](#getText--) | Aranıp eşleşmesi gerekiyorsa Barkod İmza metnini belirtir. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Aranıp eşleşmesi gerekiyorsa Barkod İmza metnini belirtir. |
|
|  | [getMatchType()](#getMatchType--) | Barkod metin Eşleşme Türü aramasını alır veya ayarlar. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Barkod metin Eşleşme Türü aramasını alır veya ayarlar. |
|
|  | [getReturnContent()](#getReturnContent--) | Belge sayfasındaki imzanın Barkod görüntü içeriğini yakalama bayrağını alır veya ayarlar. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Belge sayfasındaki imzanın Barkod görüntü içeriğini yakalama bayrağını alır veya ayarlar. |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent özelliği etkin olduğunda Barcode imzasının döndürülen görüntü içeriğinin dosya türünü belirtir. |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


SearchBarcodeOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


SearchBarcodeOptions sınıfının yeni bir örneğini kodlama türü değeriyle başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barkod kodlama türünü belirtir. |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


SearchBarcodeOptions sınıfının yeni bir örneğini kodlama türü ve metin değerleriyle başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barkod kodlama türünü belirtir. |
|
|  | metin | java.lang.String | Barkod imzasının Metnini ayarla. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Barkodları aramak için Kodlama Türü özelliğini belirtir.
Bu değer ayarlanmamışsa, arama desteklenen tüm Barkod Türleri için işlenir


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Barkodları aramak için Kodlama Türü özelliğini belirtir.
Bu değer ayarlanmamışsa, arama desteklenen tüm Barkod Türleri için işlenir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Aranıp eşleşmesi gerekiyorsa Barkod İmza metnini belirtir.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Aranıp eşleşmesi gerekiyorsa Barkod İmza metnini belirtir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Barkod metin Eşleşme Türü aramasını alır veya ayarlar. Yalnızca Metin özelliği ayarlandığında kullanılır.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Barkod metin Eşleşme Türü aramasını alır veya ayarlar. Yalnızca Metin özelliği ayarlandığında kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Belge sayfasındaki imzanın Barkod görüntü içeriğini yakalama bayrağını alır veya ayarlar.
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


Belge sayfasındaki imzanın Barkod görüntü içeriğini yakalama bayrağını alır veya ayarlar.
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
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Olası desteklenen değerler: FileType.JPEG, FileType.PNG, FileType.BMP.
Sağlanan format desteklenmiyorsa, Barcode görüntü içeriği .png formatında döndürülecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

