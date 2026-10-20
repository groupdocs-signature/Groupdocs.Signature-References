---
title: "ProcessLog"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar detaljer om dokumentprocessen."
type: docs
weight: 15
url: /sv/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Representerar detaljer om dokumentprocessen.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getDate()](#getDate--) | Hämta processens datum och tid. |
|
|  | [getType()](#getType--) | Hämta processens typ. |
|
|  | [getMessage()](#getMessage--) | Hämta processens beskrivning. |
|
|  | [getSucceeded()](#getSucceeded--) | Antal framgångsrikt bearbetade signaturer. |
|
|  | [getFailed()](#getFailed--) | Antal signaturer som misslyckades under bearbetning. |
|
|  | [getSignatures()](#getSignatures--) | Listan över framgångsrikt bearbetade signaturer. |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


Hämta processens datum och tid.


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Hämta processens typ.


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Hämta processens beskrivning.


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Antal framgångsrikt bearbetade signaturer.


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Antal signaturer som misslyckades under bearbetning.


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Listan över framgångsrikt bearbetade signaturer.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
