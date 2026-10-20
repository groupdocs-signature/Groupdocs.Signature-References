---
title: "ProcessLog"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Geeft weer details van het documentproces."
type: docs
weight: 15
url: /nl/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Geeft weer details van het documentproces.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getDate()](#getDate--) | Haal de datum en tijd van het proces op. |
|
|  | [getType()](#getType--) | Haal het type proces op. |
|
|  | [getMessage()](#getMessage--) | Haal de beschrijving van het proces op. |
|
|  | [getSucceeded()](#getSucceeded--) | Aantal succesvol verwerkte handtekeningen. |
|
|  | [getFailed()](#getFailed--) | Aantal handtekeningen die tijdens de verwerking zijn mislukt. |
|
|  | [getSignatures()](#getSignatures--) | De lijst met succesvol verwerkte handtekeningen. |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


Haal de datum en tijd van het proces op.


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Haal het type proces op.


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Haal de beschrijving van het proces op.


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Aantal succesvol verwerkte handtekeningen.


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Aantal handtekeningen die tijdens de verwerking zijn mislukt.


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


De lijst met succesvol verwerkte handtekeningen.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
