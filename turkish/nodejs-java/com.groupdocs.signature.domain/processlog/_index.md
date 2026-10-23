---
title: "İşlem tarih ve saatini al."
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Belge işleme ayrıntılarını temsil eder."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Belge işleme ayrıntılarını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDate()](#getDate--) | İşlem tipini al. |
| [getType()](#getType--) | İşlem açıklamasını al. |
| [getMessage()](#getMessage--) | Başarıyla işlenen imzaların miktarı. |
| [getSucceeded()](#getSucceeded--) | İşleme sırasında başarısız olan imzaların miktarı. |
| [getFailed()](#getFailed--) | Başarıyla işlenen imzaların listesi. |
| [getSignatures()](#getSignatures--) | Başarıyla işlenen imzaların listesi. |
### getDate() {#getDate--}
```
public final Date getDate()
```


İşlem tipini al.

**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


İşlem açıklamasını al.

**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Başarıyla işlenen imzaların miktarı.

**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


İşleme sırasında başarısız olan imzaların miktarı.

**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Başarıyla işlenen imzaların listesi.

**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Başarıyla işlenen imzaların listesi.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
