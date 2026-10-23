---
title: "SignResult"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Yeni oluşturulan imzalarla belge için imzalama sürecinin sonucu."
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Yeni oluşturulan imzalarla belge için imzalama sürecinin sonucu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | İşlemin yürütülme süresini milisaniye cinsinden döndürür |
| [getTotalSignatures()](#getTotalSignatures--) | Toplam işlenen imzaları döndürür |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Kaynak belge boyutunu döndürür |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Hedef belge boyutunu döndürür |
| [getSucceeded()](#getSucceeded--) | Yeni oluşturulan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Oluşturulması başarısız olan imzaların listesi. |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


İşlemin yürütülme süresini milisaniye cinsinden döndürür

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


Yeni oluşturulan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Oluşturulması başarısız olan imzaların listesi.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
