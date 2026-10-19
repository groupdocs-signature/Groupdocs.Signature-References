---
title: "EPC"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει τον Κώδικα Γρήγορης Απόκρισης του European Payments Council."
type: docs
weight: 14
url: /el/java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Αντιπροσωπεύει τον Κώδικα Γρήγορης Απόκρισης του European Payments Council.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EPC()](#EPC--) | Δημιουργεί νέο αντικείμενο EPC. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Λαμβάνει ή ορίζει το Όνομα του Δικαιούχου. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Λαμβάνει ή ορίζει το Όνομα του Δικαιούχου. |
|
|  | [getBIC()](#getBIC--) | Λαμβάνει ή ορίζει το BIC του Δικαιούχου με μέγιστο μήκος 11 χαρακτήρων. |
|
|  | [setBIC(String value)](#setBIC-java.lang.String-) | Λαμβάνει ή ορίζει το BIC του Δικαιούχου με μέγιστο μήκος 11 χαρακτήρων. |
|
|  | [getIBAN()](#getIBAN--) | Λαμβάνει ή ορίζει τον Λογαριασμό του Δικαιούχου (IBAN). |
|
|  | [setIBAN(String value)](#setIBAN-java.lang.String-) | Λαμβάνει ή ορίζει τον Λογαριασμό του Δικαιούχου (IBAN). |
|
|  | [getAmount()](#getAmount--) | Λαμβάνει ή ορίζει το ποσό. |
|
|  | [setAmount(double value)](#setAmount-double-) | Λαμβάνει ή ορίζει το ποσό. |
|
|  | [getCode()](#getCode--) | Λαμβάνει ή ορίζει τον Κωδικό Επιχείρησης με έως 4 χαρακτήρες. |
|
|  | [setCode(String value)](#setCode-java.lang.String-) | Λαμβάνει ή ορίζει τον Κωδικό Επιχείρησης με έως 4 χαρακτήρες. |
|
|  | [getReference()](#getReference--) | Λαμβάνει ή ορίζει την Αναφορά Πληρωμής (μέγιστο 35 χαρακτήρες). |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Λαμβάνει ή ορίζει την Αναφορά Πληρωμής (μέγιστο 35 χαρακτήρες). |
|
|  | [getRemittance()](#getRemittance--) | Λαμβάνει ή ορίζει τις Πληροφορίες Εμβάσματος (μέγιστο 140 χαρακτήρες). |
|
|  | [setRemittance(String value)](#setRemittance-java.lang.String-) | Λαμβάνει ή ορίζει τις Πληροφορίες Εμβάσματος (μέγιστο 140 χαρακτήρες). |
|
|  | [getInformation()](#getInformation--) | Λαμβάνει ή ορίζει πληροφορίες υπόδειξης. |
|
|  | [setInformation(String value)](#setInformation-java.lang.String-) | Λαμβάνει ή ορίζει πληροφορίες υπόδειξης. |
|
|  | [getVersion()](#getVersion--) | Υλοποίηση έκδοσης EPC / SEPA QR-Code. |
|
|  | [setVersion(String value)](#setVersion-java.lang.String-) | Υλοποίηση έκδοσης EPC / SEPA QR-Code. |
|
|  | [getCharset()](#getCharset--) | Υλοποίηση συνόλου χαρακτήρων EPC / SEPA QR-Code. |
|
|  | [setCharset(String value)](#setCharset-java.lang.String-) | Υλοποίηση συνόλου χαρακτήρων EPC / SEPA QR-Code. |
|
|  | [getIdentification()](#getIdentification--) | Αναγνώριση EPC / SEPA QR-Code. |
|
|  | [setIdentification(String value)](#setIdentification-java.lang.String-) | Αναγνώριση EPC / SEPA QR-Code. |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων EPC. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
### EPC() {#EPC--}
```
public EPC()
```


Δημιουργεί νέο αντικείμενο EPC.


### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει ή ορίζει το Όνομα του Δικαιούχου. Το μέγιστο μήκος είναι 70 χαρακτήρες.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Λαμβάνει ή ορίζει το Όνομα του Δικαιούχου. Το μέγιστο μήκος είναι 70 χαρακτήρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Λαμβάνει ή ορίζει το BIC του Δικαιούχου με μέγιστο μήκος 11 χαρακτήρων.


**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Λαμβάνει ή ορίζει το BIC του Δικαιούχου με μέγιστο μήκος 11 χαρακτήρων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Λαμβάνει ή ορίζει τον Λογαριασμό του Δικαιούχου (IBAN). Το IBAN αποτελείται από έως 34 αλφαριθμητικούς χαρακτήρες.


**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Λαμβάνει ή ορίζει τον Λογαριασμό του Δικαιούχου (IBAN). Το IBAN αποτελείται από έως 34 αλφαριθμητικούς χαρακτήρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Λαμβάνει ή ορίζει το ποσό.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Λαμβάνει ή ορίζει το ποσό.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Λαμβάνει ή ορίζει τον Κωδικό Επιχείρησης με έως 4 χαρακτήρες.


**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Λαμβάνει ή ορίζει τον Κωδικό Επιχείρησης με έως 4 χαρακτήρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Λαμβάνει ή ορίζει την Αναφορά Πληρωμής (μέγιστο 35 χαρακτήρες). Αυτό το πεδίο και το πεδίο Remittance Information είναι αμοιβαία αποκλειστικά.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Λαμβάνει ή ορίζει την Αναφορά Πληρωμής (μέγιστο 35 χαρακτήρες). Αυτό το πεδίο και το πεδίο Remittance Information είναι αμοιβαία αποκλειστικά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Λαμβάνει ή ορίζει τις Πληροφορίες Πληρωμής (μέγιστο 140 χαρακτήρες). Αυτό το πεδίο και το πεδίο Payment Reference είναι αμοιβαία αποκλειστικά.


**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Λαμβάνει ή ορίζει τις Πληροφορίες Πληρωμής (μέγιστο 140 χαρακτήρες). Αυτό το πεδίο και το πεδίο Payment Reference είναι αμοιβαία αποκλειστικά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Λαμβάνει ή ορίζει πληροφορίες υπόδειξης. Μέγιστο 70 χαρακτήρες.


**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Λαμβάνει ή ορίζει πληροφορίες υπόδειξης. Μέγιστο 70 χαρακτήρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Υλοποίηση έκδοσης EPC / SEPA QR-Code. Από προεπιλογή αυτή η τιμή ορίζεται σε 002.


**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


Υλοποίηση έκδοσης EPC / SEPA QR-Code. Από προεπιλογή αυτή η τιμή ορίζεται σε 002.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


Υλοποίηση συνόλου χαρακτήρων EPC / SEPA QR-Code. Από προεπιλογή αυτή η τιμή ορίζεται σε 1.


**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


Υλοποίηση συνόλου χαρακτήρων EPC / SEPA QR-Code. Από προεπιλογή αυτή η τιμή ορίζεται σε 1.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


Αναγνώριση EPC / SEPA QR-Code. Από προεπιλογή αυτή η τιμή ορίζεται σε SCT.


**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


Αναγνώριση EPC / SEPA QR-Code. Από προεπιλογή αυτή η τιμή ορίζεται σε SCT.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Αντικαθιστά τη μέθοδο Equals για σύγκριση ιδιοτήτων EPC.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | προέλευση | java.lang.Object | Αντικείμενο EPC για σύγκριση. |
|

**Returns:**
boolean - Επιστρέφει true εάν το δοσμένο αντικείμενο διεύθυνσης έχει τον ίδιο τύπο και όλες οι ιδιότητές του είναι ίσες με τις ιδιότητες αυτού του αντικειμένου.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Αντικαθιστά τη μέθοδο GetHashCode


**Returns:**
int - κώδικας κατακερματισμού Email

