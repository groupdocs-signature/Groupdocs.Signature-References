---
title: "BarcodeSearchOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Barkod imzaları için soyut arama seçeneklerini temsil eder."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.options.search/barcodesearchoptions/
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
| [BarcodeSearchOptions()](#BarcodeSearchOptions--) | SearchBarcodeOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Encode türü değeriyle SearchBarcodeOptions sınıfının yeni bir örneğini başlatır. |
| [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Encode türü ve metin değerleriyle SearchBarcodeOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Barkodları aramak için Encode Type özelliğini belirtir. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Barkodları aramak için Encode Type özelliğini belirtir. |
| [getText()](#getText--) | Aranıp eşleşmesi gereken Barcode Signature metnini belirtir. |
| [setText(String value)](#setText-java.lang.String-) | Aranıp eşleşmesi gereken Barcode Signature metnini belirtir. |
| [getMatchType()](#getMatchType--) | Barcode metni Match Type aramasını alır veya ayarlar. |
| [setMatchType(int value)](#setMatchType-int-) | Barcode metni Match Type aramasını alır veya ayarlar. |
| [getReturnContent()](#getReturnContent--) | Belge sayfasındaki imzanın Barcode görüntü içeriğini alacak bayrağı alır veya ayarlar. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Belge sayfasındaki imzanın Barcode görüntü içeriğini alacak bayrağı alır veya ayarlar. |
| [getReturnContentType()](#getReturnContentType--) | ReturnContent özelliği etkin olduğunda Barkod imzasının döndürülen görüntü içeriğinin dosya tipini belirtir. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent özelliği etkin olduğunda Barkod imzasının döndürülen görüntü içeriğinin dosya tipini belirtir. |
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


SearchBarcodeOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Encode türü değeriyle SearchBarcodeOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode encode türünü belirtir. |

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Encode türü ve metin değerleriyle SearchBarcodeOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode encode türünü belirtir. |
| metin | java.lang.String | Barcode imzasının Metnini ayarla. |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Barkodları aramak için Encode Type özelliğini belirtir. Bu değer ayarlanmamışsa, arama desteklenen tüm Barcode Türleri için işlenir.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Barkodları aramak için Encode Type özelliğini belirtir. Bu değer ayarlanmamışsa, arama desteklenen tüm Barcode Türleri için işlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Aranıp eşleşmesi gereken Barcode Signature metnini belirtir.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Aranıp eşleşmesi gereken Barcode Signature metnini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Barcode metni Match Type aramasını alır veya ayarlar. Yalnızca Text özelliği ayarlandığında kullanılır.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Barcode metni Match Type aramasını alır veya ayarlar. Yalnızca Text özelliği ayarlandığında kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Belge sayfasındaki imzanın Barcode görüntü içeriğini alacak bayrağı alır veya ayarlar. Bu bayrak true olarak ayarlanırsa, Barcode imza görüntü içeriği, gerekli format ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)) tarafından ham görüntü verisini tutar. Varsayılan olarak bu seçenek devre dışıdır.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Belge sayfasındaki imzanın Barcode görüntü içeriğini alacak bayrağı alır veya ayarlar. Bu bayrak true olarak ayarlanırsa, Barcode imza görüntü içeriği, gerekli format ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)) tarafından ham görüntü verisini tutar. Varsayılan olarak bu seçenek devre dışıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


ReturnContent özelliği etkin olduğunda Barkod imzasının döndürülen görüntü içeriğinin dosya tipini belirtir. Varsayılan olarak Null ayarlanmıştır. Bu, Barkod görüntü içeriğinin orijinal formatta döndürüleceği anlamına gelir. Bu görüntü formatı, BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) adresinde belirtilir. Desteklenen olası değerler: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan format desteklenmezse, Barkod görüntü içeriği .png formatında döndürülür.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent özelliği etkin olduğunda Barkod imzasının döndürülen görüntü içeriğinin dosya tipini belirtir. Varsayılan olarak Null ayarlanmıştır. Bu, Barkod görüntü içeriğinin orijinal formatta döndürüleceği anlamına gelir. Bu görüntü formatı, BarcodeSignature.Format ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}) adresinde belirtilir. Desteklenen olası değerler: FileType.JPEG, FileType.PNG, FileType.BMP. Sağlanan format desteklenmezse, Barkod görüntü içeriği .png formatında döndürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

