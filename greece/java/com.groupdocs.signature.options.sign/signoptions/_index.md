---
title: "SignOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει τις επιλογές υπογραφής."
type: docs
weight: 16
url: /el/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

Αντιπροσωπεύει τις επιλογές υπογραφής.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή. |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή. |
|
|  | [getAllPages()](#getAllPages--) | Τοποθετήστε την υπογραφή σε όλες τις σελίδες του εγγράφου. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Τοποθετήστε την υπογραφή σε όλες τις σελίδες του εγγράφου. |
|
|  | [getAppearance()](#getAppearance--) | Πρόσθετη εμφάνιση υπογραφής. |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Πρόσθετη εμφάνιση υπογραφής. |
|
|  | [getExtensions()](#getExtensions--) | Επεκτάσεις υπογραφής. |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | Επεκτάσεις υπογραφής. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. |
|
|  | [getSignatureType()](#getSignatureType--) | Λάβετε τον τύπο υπογραφής [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | Λάβετε ή ορίστε τον τύπο εγγράφου των επιλογών υπογραφής [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | Λάβετε ή ορίστε τον τύπο εγγράφου των επιλογών υπογραφής [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | Λαμβάνει ή ορίζει τη θέση Z-order της υπογραφής κειμένου. |
|
|  | [setZOrder(int value)](#setZOrder-int-) | Λαμβάνει ή ορίζει τη θέση Z-order της υπογραφής κειμένου. |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | Λαμβάνει ή ορίζει τον αλγόριθμο κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες. |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Λαμβάνει ή ορίζει τον αλγόριθμο κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες. |
|
|  | [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς. |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή.
Η ελάχιστη και προεπιλεγμένη τιμή είναι 1.


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για υπογραφή.
Η ελάχιστη και προεπιλεγμένη τιμή είναι 1.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


Τοποθετήστε την υπογραφή σε όλες τις σελίδες του εγγράφου.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


Τοποθετήστε την υπογραφή σε όλες τις σελίδες του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Πρόσθετη εμφάνιση υπογραφής.


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Πρόσθετη εμφάνιση υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


Επεκτάσεις υπογραφής.


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


Επεκτάσεις υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Λάβετε τον τύπο υπογραφής [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


Λάβετε ή ορίστε τον τύπο εγγράφου των επιλογών υπογραφής [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


Λάβετε ή ορίστε τον τύπο εγγράφου των επιλογών υπογραφής [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Λαμβάνει ή ορίζει τη θέση Z-order της υπογραφής κειμένου.
Καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών.


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Λαμβάνει ή ορίζει τη θέση Z-order της υπογραφής κειμένου.
Καθορίζει τη σειρά εμφάνισης των επικαλυπτόμενων υπογραφών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


Λαμβάνει ή ορίζει τον αλγόριθμο κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες.
Υποστηρίζεται αποκλειστικά για ψηφιακές υπογραφές σε αρχεία PDF.
Η τιμή είναι μία από τις σταθερές στο [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm).


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Λαμβάνει ή ορίζει τον αλγόριθμο κατακερματισμού που θα χρησιμοποιηθεί για κρυπτογραφικές λειτουργίες.
Υποστηρίζεται αποκλειστικά για ψηφιακές υπογραφές σε αρχεία PDF.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς.


**Returns:**
java.lang.String - 
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
