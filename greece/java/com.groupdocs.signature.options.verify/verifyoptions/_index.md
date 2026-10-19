---
title: "VerifyOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Διατηρεί επιλογές για επαλήθευση εγγράφου."
type: docs
weight: 15
url: /el/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Διατηρεί επιλογές για επαλήθευση εγγράφου.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid()](#isValid--) | Ένδειξη έγκυρης ιδιότητας. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Ένδειξη έγκυρης ιδιότητας. |
|
|  | [getPageNumber()](#getPageNumber--) | Αριθμός σελίδας εγγράφου προς επαλήθευση. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Αριθμός σελίδας εγγράφου προς επαλήθευση. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Επιλογές σελίδας για τον καθορισμό των σελίδων που θα επαληθευτούν. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Επιλογές σελίδας για τον καθορισμό των σελίδων που θα επαληθευτούν. |
|
|  | [getAllPages()](#getAllPages--) | Ένδειξη για επαλήθευση κάθε σελίδας του εγγράφου. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Ένδειξη για επαλήθευση κάθε σελίδας του εγγράφου. |
|
|  | [getExtensions()](#getExtensions--) | Πρόσθετες επεκτάσεις για την επαλήθευση εναλλακτικών επιλογών υπογραφής. |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Πρόσθετες επεκτάσεις για την επαλήθευση εναλλακτικών επιλογών υπογραφής. |
|
|  | [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς. |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


Ένδειξη έγκυρης ιδιότητας.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Ένδειξη έγκυρης ιδιότητας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Αριθμός σελίδας εγγράφου προς επαλήθευση. Εάν η ιδιότητα δεν οριστεί - όλες οι σελίδες του
Το έγγραφο θα επαληθευτεί για την πρώτη εμφάνιση.
Η ελάχιστη τιμή είναι 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Αριθμός σελίδας εγγράφου προς επαλήθευση. Εάν η ιδιότητα δεν οριστεί - όλες οι σελίδες του
Το έγγραφο θα επαληθευτεί για την πρώτη εμφάνιση.
Η ελάχιστη τιμή είναι 1.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Επιλογές σελίδας για τον καθορισμό των σελίδων που θα επαληθευτούν.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Επιλογές σελίδας για τον καθορισμό των σελίδων που θα επαληθευτούν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Ένδειξη για επαλήθευση κάθε σελίδας του εγγράφου. Η προεπιλεγμένη τιμή είναι true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Ένδειξη για επαλήθευση κάθε σελίδας του εγγράφου. Η προεπιλεγμένη τιμή είναι true.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Πρόσθετες επεκτάσεις για την επαλήθευση εναλλακτικών επιλογών υπογραφής.


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Πρόσθετες επεκτάσεις για την επαλήθευση εναλλακτικών επιλογών υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς.


**Returns:**
java.lang.String - 
