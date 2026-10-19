---
title: "SignResult"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αποτέλεσμα της διαδικασίας υπογραφής εγγράφου με νέες δημιουργημένες υπογραφές."
type: docs
weight: 17
url: /el/java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Αποτέλεσμα της διαδικασίας υπογραφής εγγράφου με νέες δημιουργημένες υπογραφές.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Επιστρέφει το χρόνο εκτέλεσης της διαδικασίας σε χιλιοστά του δευτερολέπτου |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Επιστρέφει το συνολικό αριθμό επεξεργασμένων υπογραφών |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Επιστρέφει το μέγεθος του πηγαίου εγγράφου |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Επιστρέφει το μέγεθος του εγγράφου προορισμού |
|
|  | [getSucceeded()](#getSucceeded--) | Λίστα των νεοδημιουργημένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Λίστα των υπογραφών που απέτυχαν να δημιουργηθούν. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Επιστρέφει το χρόνο εκτέλεσης της διαδικασίας σε χιλιοστά του δευτερολέπτου


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Επιστρέφει το συνολικό αριθμό επεξεργασμένων υπογραφών


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Επιστρέφει το μέγεθος του πηγαίου εγγράφου


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Επιστρέφει το μέγεθος του εγγράφου προορισμού


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Λίστα των νεοδημιουργημένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Λίστα των υπογραφών που απέτυχαν να δημιουργηθούν.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
