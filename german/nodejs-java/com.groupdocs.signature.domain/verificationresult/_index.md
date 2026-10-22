---
title: "VerificationResult"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Instanz zum Speichern der Ergebnisse des Verifizierungsprozesses."
type: docs
weight: 20
url: /de/nodejs-java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Instanz zum Speichern der Ergebnisse des Verifizierungsprozesses.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Gibt die Ausführungszeit des Prozesses in Millisekunden zurück. |
| [getTotalSignatures()](#getTotalSignatures--) | Gibt die Gesamtzahl der verarbeiteten Signaturen zurück |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Gibt die Größe des Quelldokuments in Bytes zurück |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Gibt die Größe des Zieldokuments zurück. |
| [getSucceeded()](#getSucceeded--) | Liste erfolgreich verifizierter Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [isValid()](#isValid--) | Gibt true zurück, wenn der Verifizierungsprozess erfolgreich war, andernfalls false. |
| [setValid(boolean value)](#setValid-boolean-) | Gibt true zurück, wenn der Verifizierungsprozess erfolgreich war, andernfalls false. |
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


Gibt die Gesamtzahl der verarbeiteten Signaturen zurück

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Gibt die Größe des Quelldokuments in Bytes zurück

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Gibt die Größe des Zieldokuments zurück. Für die Verifizierung enthält diese Variable immer null.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Liste der erfolgreich verifizierten Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Diese Eigenschaft wird derzeit nicht unterstützt.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Gibt true zurück, wenn der Verifizierungsprozess erfolgreich war, andernfalls false.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Gibt true zurück, wenn der Verifizierungsprozess erfolgreich war, andernfalls false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

