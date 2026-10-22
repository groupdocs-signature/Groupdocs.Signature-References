---
title: "SearchOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει τις επιλογές εξαγωγής υπογραφών από το έγγραφο."
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Αντιπροσωπεύει τις επιλογές εξαγωγής υπογραφών από το έγγραφο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για αναζήτηση. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για αναζήτηση. |
| [getPagesSetup()](#getPagesSetup--) | Επιλογές για τον καθορισμό σελίδων για την αναζήτηση Υπογραφής. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Επιλογές για τον καθορισμό σελίδων για την αναζήτηση Υπογραφής. |
| [getAllPages()](#getAllPages--) | Σημαία για αναζήτηση σε κάθε σελίδα του εγγράφου. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Σημαία για αναζήτηση σε κάθε σελίδα του εγγράφου. |
| [getSkipExternal()](#getSkipExternal--) | Σημαία για επιστροφή μόνο των υπογραφών που έχουν σημειωθεί ως IsSignature. |
| [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Σημαία για επιστροφή μόνο των υπογραφών που έχουν σημειωθεί ως IsSignature. |
| [getSearchPages(int totalPages)](#getSearchPages-int-) | Εικονική μέθοδος για λήψη λίστας σελίδων για εξαγωγή Υπογραφής. |
| [toString()](#toString--) | Παρακάμπτει τη μετατροπή σε συμβολοσειρά. |
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για αναζήτηση. Η τιμή είναι προαιρετική.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για αναζήτηση. Η τιμή είναι προαιρετική.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Επιλογές για τον καθορισμό σελίδων για την αναζήτηση Υπογραφής.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Επιλογές για τον καθορισμό σελίδων για την αναζήτηση Υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Σημαία για αναζήτηση σε κάθε σελίδα του εγγράφου. Από προεπιλογή αυτή η τιμή ορίζεται σε true.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Σημαία για αναζήτηση σε κάθε σελίδα του εγγράφου. Από προεπιλογή αυτή η τιμή ορίζεται σε true.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Σημαία για επιστροφή μόνο των υπογραφών που έχουν σημειωθεί ως IsSignature. Από προεπιλογή η τιμή είναι false, που υποδεικνύει την επιστροφή όλων των υπογραφών που ταιριάζουν με τα καθορισμένα κριτήρια.

**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Σημαία για επιστροφή μόνο των υπογραφών που έχουν σημειωθεί ως IsSignature. Από προεπιλογή η τιμή είναι false, που υποδεικνύει την επιστροφή όλων των υπογραφών που ταιριάζουν με τα καθορισμένα κριτήρια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Εικονική μέθοδος για λήψη λίστας σελίδων για εξαγωγή Υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| totalPages | int | Συνολικός αριθμός σελίδων |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Λίστα αριθμών σελίδων
### toString() {#toString--}
```
public String toString()
```


Παρακάμπτει τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
