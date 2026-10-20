---
title: "UpdateResult"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belgedeki imzaların değiştirilmesinin sonucu."
type: docs
weight: 19
url: /tr/java/com.groupdocs.signature.domain/updateresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class UpdateResult implements IResult
```

Belgedeki imzaların değiştirilmesinin sonucu.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | İşlemin yürütme süresini milisaniye cinsinden döndürür |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Toplam işlenen imzaları döndürür |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Kaynak belge boyutunu döndürür |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Hedef belge boyutunu döndürür |
|
|  | [getSucceeded()](#getSucceeded--) | Başarıyla değiştirilmiş imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Güncellenmemiş imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
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


Başarıyla değiştirilmiş imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Güncellenmemiş imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
