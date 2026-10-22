---
title: "SearchResult"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αποτέλεσμα της αναζήτησης υπογραφών στο καθορισμένο έγγραφο."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Αποτέλεσμα της αναζήτησης υπογραφών στο καθορισμένο έγγραφο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Επιστρέφει το χρόνο εκτέλεσης της διαδικασίας αναζήτησης σε χιλιοστά του δευτερολέπτου. |
| [getTotalSignatures()](#getTotalSignatures--) | Επιστρέφει το συνολικό αριθμό επεξεργασμένων υπογραφών από τη διαδικασία αναζήτησης |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Επιστρέφει το μέγεθος του πηγαίου εγγράφου |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Επιστρέφει το μέγεθος του προορισμού εγγράφου. |
| [getSucceeded()](#getSucceeded--) | Λίστα των ευρεθέντων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Λίστα των υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) που απέτυχαν στη διαδικασία Αναζήτησης βάσει κριτηρίων αναζήτησης. |
| [getSignatures()](#getSignatures--) | Λίστα των εντοπισμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Παρέχει μετατροπή σε λίστα υπογραφών με ισχυρά τυποποιημένα στοιχεία. |
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Επιστρέφει το χρόνο εκτέλεσης της διαδικασίας αναζήτησης σε χιλιοστά του δευτερολέπτου.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Επιστρέφει το συνολικό αριθμό επεξεργασμένων υπογραφών από τη διαδικασία αναζήτησης

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


Επιστρέφει το μέγεθος του προορισμού εγγράφου. Για τη μέθοδο Search επιστρέφει πάντα 0.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Λίστα των ευρεθέντων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Αυτή η λίστα θα είναι πάντα ίση με την ιδιότητα Signatures (\#getSignatures.getSignatures/\#setSignatures(List).setSignatures(List)).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Λίστα των υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) που απέτυχαν στη διαδικασία Αναζήτησης βάσει κριτηρίων αναζήτησης. Δεν υποστηρίζεται στην τρέχουσα έκδοση.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Λίστα των εντοπισμένων υπογραφών [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Παρέχει μετατροπή σε λίστα υπογραφών με ισχυρά τυποποιημένα στοιχεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Επιστρέφει λίστα του δεδομένου τύπου υπογραφής.

T : Ο τύπος των υπογραφών στη λίστα.
### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

