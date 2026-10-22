---
title: "UpdateResult"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Ergebnis der Modifikation von Signaturen im Dokument."
type: docs
weight: 19
url: /de/nodejs-java/com.groupdocs.signature.domain/updateresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class UpdateResult implements IResult
```

Ergebnis der Modifikation von Signaturen im Dokument.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Gibt die Ausführungszeit des Prozesses in Millisekunden zurück |
| [getTotalSignatures()](#getTotalSignatures--) | Gibt die Gesamtzahl der verarbeiteten Signaturen zurück |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Gibt die Größe des Quelldokuments zurück |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Gibt die Größe des Zieldokuments zurück |
| [getSucceeded()](#getSucceeded--) | Liste der erfolgreich modifizierten Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Liste der Signaturen, die nicht aktualisiert wurden [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Gibt die Ausführungszeit des Prozesses in Millisekunden zurück

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Gibt die Gesamtzahl der verarbeiteten Signaturen zurück

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Gibt die Größe des Quelldokuments zurück

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Gibt die Größe des Zieldokuments zurück

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Liste der erfolgreich modifizierten Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Liste der Signaturen, die nicht aktualisiert wurden [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
