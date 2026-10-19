---
title: "BaseSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιγράφει τη βασική κλάση για υπογραφές."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Περιγράφει τη βασική κλάση για υπογραφές.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | Καθορίζει τον τύπο της υπογραφής. |
|
|  | [getPageNumber()](#getPageNumber--) | Καθορίζει τη σελίδα στην οποία βρέθηκε η υπογραφή. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Καθορίζει τη σελίδα στην οποία βρέθηκε η υπογραφή. |
|
|  | [getSignatureId()](#getSignatureId--) | Μοναδικό αναγνωριστικό υπογραφής για την τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων Update ή Delete. |
|
|  | [isSignature()](#isSignature--) | Λάβετε ή ορίστε τη σημαία για να υποδείξετε εάν αυτό το στοιχείο είναι Υπογραφή ή περιεχόμενο εγγράφου. |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | Λάβετε ή ορίστε τη σημαία για να υποδείξετε εάν αυτό το στοιχείο είναι Υπογραφή ή περιεχόμενο εγγράφου. |
|
|  | [getDeleted()](#getDeleted--) | Λάβετε ή ορίστε τη σημαία για να υποδείξετε εάν αυτή η υπογραφή διαγράφηκε από το έγγραφο. |
|
|  | [getCreatedOn()](#getCreatedOn--) | Λάβετε ή ορίστε την ημερομηνία δημιουργίας της υπογραφής. |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Λάβετε ή ορίστε την ημερομηνία δημιουργίας της υπογραφής. |
|
|  | [getModifiedOn()](#getModifiedOn--) | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής. |
|
|  | [getTop()](#getTop--) | Καθορίζει την άνω θέση της υπογραφής. |
|
|  | [setTop(int value)](#setTop-int-) | Καθορίζει την άνω θέση της υπογραφής. |
|
|  | [getLeft()](#getLeft--) | Καθορίζει την αριστερή θέση της υπογραφής. |
|
|  | [setLeft(int value)](#setLeft-int-) | Καθορίζει την αριστερή θέση της υπογραφής. |
|
|  | [getWidth()](#getWidth--) | Καθορίζει το πλάτος της υπογραφής. |
|
|  | [setWidth(int value)](#setWidth-int-) | Καθορίζει το πλάτος της υπογραφής. |
|
|  | [getHeight()](#getHeight--) | Καθορίζει το ύψος της υπογραφής. |
|
|  | [setHeight(int value)](#setHeight-int-) | Καθορίζει το ύψος της υπογραφής. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Καθορίζει τον τύπο της υπογραφής. Η ψηφιακή υπογραφή θα έχει αυτήν την ιδιότητα.


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Καθορίζει τη σελίδα στην οποία βρέθηκε η υπογραφή.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Καθορίζει τη σελίδα στην οποία βρέθηκε η υπογραφή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Μοναδικό αναγνωριστικό υπογραφής για την τροποποίηση της υπογραφής στο έγγραφο μέσω των μεθόδων Update ή Delete.
Αυτή η ιδιότητα θα οριστεί αυτόματα μετά την κλήση της μεθόδου Sign ή Search.
Εάν αυτή η ιδιότητα είχε αποθηκευτεί προηγουμένως, μπορεί να οριστεί χειροκίνητα για να τροποποιηθεί η υπογραφή.


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Λάβετε ή ορίστε τη σημαία για να υποδείξετε εάν αυτό το στοιχείο είναι Υπογραφή ή περιεχόμενο εγγράφου.
Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο Update για να ορίσει το στοιχείο ως υπογραφή (true) ή ως στοιχείο εγγράφου (false).


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Λάβετε ή ορίστε τη σημαία για να υποδείξετε εάν αυτό το στοιχείο είναι Υπογραφή ή περιεχόμενο εγγράφου.
Αυτή η ιδιότητα χρησιμοποιείται με τη μέθοδο Update για να ορίσει το στοιχείο ως υπογραφή (true) ή ως στοιχείο εγγράφου (false).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Λάβετε ή ορίστε τη σημαία για να υποδείξετε εάν αυτή η υπογραφή διαγράφηκε από το έγγραφο.
Αυτή η ιδιότητα χρησιμοποιείται μόνο για τις εγγραφές του ιστορικού εγγράφου ώστε να διατηρεί τη λίστα των διαγραμμένων υπογραφών.


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Λάβετε ή ορίστε την ημερομηνία δημιουργίας της υπογραφής.


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Λάβετε ή ορίστε την ημερομηνία δημιουργίας της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής.


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Λάβετε ή ορίστε την ημερομηνία τροποποίησης της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Καθορίζει την άνω θέση της υπογραφής.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Καθορίζει την άνω θέση της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Καθορίζει την αριστερή θέση της υπογραφής.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Καθορίζει την αριστερή θέση της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Καθορίζει το πλάτος της υπογραφής.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Καθορίζει το πλάτος της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Καθορίζει το ύψος της υπογραφής.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Καθορίζει το ύψος της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | υπογραφή | java.lang.Object | Αντικείμενο υπογραφής για σύγκριση. |
|

**Returns:**
boolean - Επιστρέφει true εάν το περασμένο αντικείμενο υπογραφής έχει τον ίδιο τύπο και όλες οι ιδιότητές του είναι ίσες με τις ιδιότητες αυτού του αντικειμένου.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Αντικαθιστά τη μέθοδο GetHashCode


**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String - 
