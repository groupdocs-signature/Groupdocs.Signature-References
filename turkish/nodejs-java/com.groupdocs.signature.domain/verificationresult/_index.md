---
title: "VerificationResult"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Doğrulama sürecinin sonuçlarını tutmak için örnek."
type: docs
weight: 20
url: /tr/nodejs-java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Doğrulama sürecinin sonuçlarını tutmak için örnek.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | İşlemin yürütme süresini milisaniye cinsinden döndürür. |
| [getTotalSignatures()](#getTotalSignatures--) | Toplam işlenen imzaları döndürür |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Kaynak belgenin boyutunu bayt cinsinden döndürür. |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Hedef belgenin boyutunu döndürür. |
| [getSucceeded()](#getSucceeded--) | Başarıyla doğrulanan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [isValid()](#isValid--) | Doğrulama işlemi başarılıysa true, aksi takdirde false döndürür. |
| [setValid(boolean value)](#setValid-boolean-) | Doğrulama işlemi başarılıysa true, aksi takdirde false döndürür. |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


İşlemin yürütme süresini milisaniye cinsinden döndürür.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Toplam işlenen imzaları döndürür

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Kaynak belgenin boyutunu bayt cinsinden döndürür.

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Hedef belgenin boyutunu döndürür. Doğrulama için bu değişken her zaman sıfır içerir.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Başarıyla doğrulanan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Şu anda bu özellik desteklenmemektedir.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Doğrulama işlemi başarılıysa true, aksi takdirde false döndürür.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Doğrulama işlemi başarılıysa true, aksi takdirde false döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

