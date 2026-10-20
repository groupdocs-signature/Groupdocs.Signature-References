---
title: "DocumentResultSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Yeni oluşturulan imzalarla belge için arşiv belge imzalama sürecinin sonucu."
type: docs
weight: 13
url: /tr/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Yeni oluşturulan imzalarla belge için arşiv belge imzalama sürecinin sonucu.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFileName()](#getFileName--) | Belge dosya adı |
|
|  | [getProcessingTime()](#getProcessingTime--) | İşlemin yürütme süresini milisaniye cinsinden döndürür |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Toplam işlenen imzaları döndürür |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Kaynak belge boyutunu döndürür |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Hedef belge boyutunu döndürür |
|
|  | [getSucceeded()](#getSucceeded--) | Başarıyla işlenen imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | İşlem sırasında başarısız olan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | Belge hata ile işlendiğinde bu özellik hata mesajını içerir |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Belge dosya adı


**Returns:**
java.lang.String
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


İşlemin yürütme süresini milisaniye cinsinden döndürür


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


Kaynak belge boyutunu döndürür


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Hedef belge boyutunu döndürür


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Başarıyla işlenen imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


İşlem sırasında başarısız olan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


Belge hata ile işlendiğinde bu özellik hata mesajını içerir


**Returns:**
java.lang.String
