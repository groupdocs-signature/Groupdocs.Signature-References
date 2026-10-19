---
title: "UpdateResult"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αποτέλεσμα τροποποίησης υπογραφών στο έγγραφο."
type: docs
weight: 19
url: /el/java/com.groupdocs.signature.domain/updateresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class UpdateResult implements IResult
```

Αποτέλεσμα τροποποίησης υπογραφών στο έγγραφο.

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
|  | [getSucceeded()](#getSucceeded--) | Λίστα των υπογραφών που τροποποιήθηκαν επιτυχώς [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Λίστα των υπογραφών που δεν ενημερώθηκαν [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
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


Λίστα των υπογραφών που τροποποιήθηκαν επιτυχώς [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Λίστα των υπογραφών που δεν ενημερώθηκαν [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
