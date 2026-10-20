---
title: "DeleteResult"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belgeden imzaların silinmesinin sonucu."
type: docs
weight: 12
url: /tr/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Belgeden imza(ların) silinmesinin sonucu.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | İşlemin yürütülme süresini milisaniye cinsinden döndürür. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | İşlenen toplam imzaları döndürür. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Kaynak belge boyutunu döndürür. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Güncellenmiş belge boyutunu döndürür. |
|
|  | [getSucceeded()](#getSucceeded--) | Başarıyla silinen imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Silinmeyen imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


İşlemin yürütülme süresini milisaniye cinsinden döndürür.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


İşlenen toplam imzaları döndürür.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Kaynak belge boyutunu döndürür.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Güncellenmiş belge boyutunu döndürür.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Başarıyla silinen imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Silinmeyen imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
