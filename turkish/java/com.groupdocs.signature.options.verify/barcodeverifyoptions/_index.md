---
title: "BarcodeVerifyOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Barkod doğrulama seçeneklerini temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Barkod doğrulama seçeneklerini temsil eder.

<br />

*** ** * ** ***

 **Learn more**  **Learn more**

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](../https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](../)

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Barkod İmzası için varsayılan Doğrulama Seçeneği oluşturur. |
|
|  | [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Doğrulama metniyle varsayılan Doğrulama Seçeneği oluşturur. |
|
|  | [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Barkod Türü doğrulamasıyla varsayılan Doğrulama Seçeneği oluşturur. |
|
|  | [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Barkod Türü doğrulaması ve metniyle varsayılan Doğrulama Seçeneği oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Barkod Türü doğrulamasını alır veya ayarlar. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Barkod Türü doğrulamasını alır veya ayarlar. |
|
|  | [toString()](#toString--) | Stringe dönüşümü geçersiz kılar. |
|
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Barkod İmzası için varsayılan Doğrulama Seçeneği oluşturur.


### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Doğrulama metniyle varsayılan Doğrulama Seçeneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Doğrulanacak barkod metni |
|

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Barkod Türü doğrulamasıyla varsayılan Doğrulama Seçeneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barkod Türü doğrulaması |
|

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Barkod Türü doğrulaması ve metniyle varsayılan Doğrulama Seçeneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | metin | java.lang.String | Doğrulanacak barkod metni |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barkod Türü doğrulaması |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Barkod Türü doğrulamasını alır veya ayarlar.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Barkod Türü doğrulamasını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Stringe dönüşümü geçersiz kılar.


**Returns:**
java.lang.String -
