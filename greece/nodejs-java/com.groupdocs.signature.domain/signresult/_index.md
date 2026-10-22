---
title: "SignResult"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αποτέλεσμα της διαδικασίας υπογραφής του εγγράφου με νεοδημιουργημένες υπογραφές."
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Αποτέλεσμα της διαδικασίας υπογραφής του εγγράφου με νεοδημιουργημένες υπογραφές.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Επιστρέφει το χρόνο εκτέλεσης της διαδικασίας σε χιλιοστά του δευτερολέπτου |
| [getTotalSignatures()](#getTotalSignatures--) | Επιστρέφει το σύνολο των επεξεργασμένων υπογραφών |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Επιστρέφει το μέγεθος του πηγαίου εγγράφου |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Επιστρέφει το μέγεθος του εγγράφου προορισμού |
| [getSucceeded()](#getSucceeded--) | Λίστα των νέων δημιουργημένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Λίστα των υπογραφών που απέτυχαν να δημιουργηθούν. |
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


Επιστρέφει το σύνολο των επεξεργασμένων υπογραφών

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


Λίστα των νέων δημιουργημένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Λίστα των υπογραφών που απέτυχαν να δημιουργηθούν.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
