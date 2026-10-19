---
title: "DeleteResult"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αποτέλεσμα της διαγραφής υπογραφών από το έγγραφο."
type: docs
weight: 12
url: /el/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Αποτέλεσμα διαγραφής υπογραφής(ών) από το έγγραφο.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Επιστρέφει το χρόνο εκτέλεσης της διαδικασίας σε χιλιοστά του δευτερολέπτου. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Επιστρέφει το σύνολο των επεξεργασμένων υπογραφών. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Επιστρέφει το μέγεθος του αρχικού εγγράφου. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Επιστρέφει το μέγεθος του ενημερωμένου εγγράφου. |
|
|  | [getSucceeded()](#getSucceeded--) | Λίστα των υπογραφών που διαγράφηκαν επιτυχώς [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Λίστα των υπογραφών που δεν διαγράφηκαν [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Επιστρέφει το χρόνο εκτέλεσης της διαδικασίας σε χιλιοστά του δευτερολέπτου.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Επιστρέφει το σύνολο των επεξεργασμένων υπογραφών.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Επιστρέφει το μέγεθος του αρχικού εγγράφου.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Επιστρέφει το μέγεθος του ενημερωμένου εγγράφου.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Λίστα των υπογραφών που διαγράφηκαν επιτυχώς [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Λίστα των υπογραφών που δεν διαγράφηκαν [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
