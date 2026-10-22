---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αποτέλεσμα της επεξεργασίας της διαδικασίας υπογραφής αρχείου εγγράφου για έγγραφο με νεοδημιουργημένες signatures."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Αποτέλεσμα της επεξεργασίας της διαδικασίας υπογραφής αρχείου εγγράφου για έγγραφο με νεοδημιουργημένες signatures.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFileName()](#getFileName--) | Όνομα αρχείου εγγράφου |
| [getProcessingTime()](#getProcessingTime--) | Επιστρέφει το χρόνο εκτέλεσης της διαδικασίας σε χιλιοστά του δευτερολέπτου |
| [getTotalSignatures()](#getTotalSignatures--) | Επιστρέφει το σύνολο των επεξεργασμένων υπογραφών |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Επιστρέφει το μέγεθος του πηγαίου εγγράφου |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Επιστρέφει το μέγεθος του εγγράφου προορισμού |
| [getSucceeded()](#getSucceeded--) | Λίστα των υπογραφών που επεξεργάστηκαν επιτυχώς [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Λίστα των υπογραφών που απέτυχαν κατά τη διαδικασία [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getErrorMessage()](#getErrorMessage--) | Εάν το έγγραφο επεξεργάστηκε με σφάλμα, αυτή η ιδιότητα θα περιέχει το μήνυμα σφάλματος |
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Όνομα αρχείου εγγράφου

**Returns:**
java.lang.String
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


Λίστα των υπογραφών που επεξεργάστηκαν επιτυχώς [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Λίστα των υπογραφών που απέτυχαν κατά τη διαδικασία [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


Εάν το έγγραφο επεξεργάστηκε με σφάλμα, αυτή η ιδιότητα θα περιέχει το μήνυμα σφάλματος

**Returns:**
java.lang.String
