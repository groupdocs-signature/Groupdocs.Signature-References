---
title: "VerificationResult"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Παράδειγμα για τη διατήρηση των αποτελεσμάτων της διαδικασίας επαλήθευσης."
type: docs
weight: 20
url: /el/nodejs-java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Παράδειγμα για τη διατήρηση των αποτελεσμάτων της διαδικασίας επαλήθευσης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Επιστρέφει το χρόνο εκτέλεσης της διαδικασίας σε χιλιοστά του δευτερολέπτου. |
| [getTotalSignatures()](#getTotalSignatures--) | Επιστρέφει το σύνολο των επεξεργασμένων υπογραφών |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Επιστρέφει το μέγεθος του πηγαίου εγγράφου σε bytes |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Επιστρέφει το μέγεθος του προορισμού εγγράφου. |
| [getSucceeded()](#getSucceeded--) | Λίστα των επιτυχώς επαληθευμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [isValid()](#isValid--) | Επιστρέφει true εάν η διαδικασία Επαλήθευσης ήταν επιτυχής, διαφορετικά false. |
| [setValid(boolean value)](#setValid-boolean-) | Επιστρέφει true εάν η διαδικασία Επαλήθευσης ήταν επιτυχής, διαφορετικά false. |
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


Επιστρέφει το σύνολο των επεξεργασμένων υπογραφών

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Επιστρέφει το μέγεθος του πηγαίου εγγράφου σε bytes

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Επιστρέφει το μέγεθος του προορισμού εγγράφου. Για την επαλήθευση αυτή η μεταβλητή περιέχει πάντα μηδέν.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Λίστα των επιτυχώς επαληθευμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Αυτή τη στιγμή αυτή η ιδιότητα δεν υποστηρίζεται.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Επιστρέφει true εάν η διαδικασία Επαλήθευσης ήταν επιτυχής, διαφορετικά false.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Επιστρέφει true εάν η διαδικασία Επαλήθευσης ήταν επιτυχής, διαφορετικά false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

