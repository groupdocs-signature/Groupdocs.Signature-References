---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Ergebnis der Verarbeitung des Archivdokument-Signaturvorgangs für ein Dokument mit neu erstellten Signaturen."
type: docs
weight: 13
url: /de/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Ergebnis der Verarbeitung des Archivdokument-Signaturvorgangs für ein Dokument mit neu erstellten Signaturen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFileName()](#getFileName--) | Dokumentdateiname |
|
|  | [getProcessingTime()](#getProcessingTime--) | Gibt die Ausführungszeit des Prozesses in Millisekunden zurück |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Gibt die insgesamt verarbeiteten Signaturen zurück |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Gibt die Größe des Quelldokuments zurück |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Gibt die Größe des Zieldokuments zurück |
|
|  | [getSucceeded()](#getSucceeded--) | Liste der erfolgreich verarbeiteten Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Liste der Signaturen, die während des Prozesses fehlgeschlagen sind [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | Wenn das Dokument mit einem Fehler verarbeitet wurde, enthält diese Eigenschaft die Fehlermeldung |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Dokumentdateiname


**Returns:**
java.lang.String
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


Gibt die insgesamt verarbeiteten Signaturen zurück


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


Liste der erfolgreich verarbeiteten Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Liste der Signaturen, die während des Prozesses fehlgeschlagen sind [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


Wenn das Dokument mit einem Fehler verarbeitet wurde, enthält diese Eigenschaft die Fehlermeldung


**Returns:**
java.lang.String
