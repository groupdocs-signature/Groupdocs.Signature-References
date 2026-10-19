---
title: "DeleteResult"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Ergebnis der Signaturlöschung aus dem Dokument."
type: docs
weight: 12
url: /de/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Ergebnis der Löschung von Signatur(en) aus dem Dokument.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Gibt die Ausführungszeit des Prozesses in Millisekunden zurück. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Gibt die insgesamt verarbeiteten Signaturen zurück. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Gibt die Größe des Quelldokuments zurück. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Gibt die aktualisierte Dokumentgröße zurück. |
|
|  | [getSucceeded()](#getSucceeded--) | Liste der erfolgreich gelöschten Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Liste der Signaturen, die nicht gelöscht wurden [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Gibt die Ausführungszeit des Prozesses in Millisekunden zurück.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Gibt die insgesamt verarbeiteten Signaturen zurück.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Gibt die Größe des Quelldokuments zurück.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Gibt die aktualisierte Dokumentgröße zurück.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Liste der erfolgreich gelöschten Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Liste der Signaturen, die nicht gelöscht wurden [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
