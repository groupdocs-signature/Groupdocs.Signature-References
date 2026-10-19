---
title: "ProcessLog"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt Details zum Dokumentenprozess dar."
type: docs
weight: 15
url: /de/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Stellt Details zum Dokumentenprozess dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getDate()](#getDate--) | Liefert das Prozessdatum und die Uhrzeit. |
|
|  | [getType()](#getType--) | Liefert den Prozesstyp. |
|
|  | [getMessage()](#getMessage--) | Liefert die Prozessbeschreibung. |
|
|  | [getSucceeded()](#getSucceeded--) | Anzahl der erfolgreich verarbeiteten Signaturen. |
|
|  | [getFailed()](#getFailed--) | Anzahl der Signaturen, die bei der Verarbeitung fehlgeschlagen sind. |
|
|  | [getSignatures()](#getSignatures--) | Die Liste der erfolgreich verarbeiteten Signaturen. |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


Liefert das Prozessdatum und die Uhrzeit.


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Liefert den Prozesstyp.


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Liefert die Prozessbeschreibung.


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Anzahl der erfolgreich verarbeiteten Signaturen.


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Anzahl der Signaturen, die bei der Verarbeitung fehlgeschlagen sind.


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Die Liste der erfolgreich verarbeiteten Signaturen.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
