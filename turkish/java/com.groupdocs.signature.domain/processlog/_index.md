---
title: "ProcessLog"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belge işlem detaylarını temsil eder."
type: docs
weight: 15
url: /tr/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Belge işlem detaylarını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getDate()](#getDate--) | İşlem tarih ve saatini al. |
|
|  | [getType()](#getType--) | İşlem tipini al. |
|
|  | [getMessage()](#getMessage--) | İşlem açıklamasını al. |
|
|  | [getSucceeded()](#getSucceeded--) | Başarıyla işlenen imzaların sayısı. |
|
|  | [getFailed()](#getFailed--) | İşleme sırasında başarısız olan imzaların sayısı. |
|
|  | [getSignatures()](#getSignatures--) | Başarıyla işlenen imzaların listesi. |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


İşlem tarih ve saatini al.


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


İşlem tipini al.


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


İşlem açıklamasını al.


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Başarıyla işlenen imzaların sayısı.


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


İşleme sırasında başarısız olan imzaların sayısı.


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Başarıyla işlenen imzaların listesi.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
