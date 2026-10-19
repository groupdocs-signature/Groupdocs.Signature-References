---
title: "SwissQR"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που είναι ενσωματωμένο στον κώδικα SwissQR."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που είναι ενσωματωμένο στον κώδικα SwissQR.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | Δημιουργεί ένα παράδειγμα του SwissQR. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAmount()](#getAmount--) | Λαμβάνει ή ορίζει το ποσό πληρωμής. |
|
|  | [setAmount(double value)](#setAmount-double-) | Λαμβάνει ή ορίζει το ποσό πληρωμής. |
|
|  | [getCurrency()](#getCurrency--) | Λαμβάνει ή ορίζει το νόμισμα πληρωμής. |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | Λαμβάνει ή ορίζει το νόμισμα πληρωμής. |
|
|  | [getAccount()](#getAccount--) | Λαμβάνει ή ορίζει τον αριθμό λογαριασμού του πιστωτή. |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | Λαμβάνει ή ορίζει τον αριθμό λογαριασμού του πιστωτή. |
|
|  | [getCreditor()](#getCreditor--) | Λαμβάνει ή ορίζει τη διεύθυνση του πιστωτή. |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Λαμβάνει ή ορίζει τη διεύθυνση του πιστωτή. |
|
|  | [getReference()](#getReference--) | Λαμβάνει ή ορίζει την αναφορά πληρωμής του πιστωτή. |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | Λαμβάνει ή ορίζει την αναφορά πληρωμής του πιστωτή. |
|
|  | [getDebtor()](#getDebtor--) | Λαμβάνει ή ορίζει τη διεύθυνση του οφειλέτη. |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Λαμβάνει ή ορίζει τη διεύθυνση του οφειλέτη. |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | Λαμβάνει ή ορίζει το πρόσθετο αδόμητο μήνυμα. |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Λαμβάνει ή ορίζει το πρόσθετο αδόμητο μήνυμα. |
|
|  | [getBillInformation()](#getBillInformation--) | Λαμβάνει ή ορίζει τις πρόσθετες δομημένες πληροφορίες του τιμολογίου. |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Λαμβάνει ή ορίζει τις πρόσθετες δομημένες πληροφορίες του τιμολογίου. |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Δημιουργεί ένα παράδειγμα του SwissQR.


### getAmount() {#getAmount--}
```
public final double getAmount()
```


Λαμβάνει ή ορίζει το ποσό πληρωμής.
Οι έγκυρες τιμές είναι μεταξύ 0.01 και 999,999,999.99.
Τιμή: Το ποσό πληρωμής.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Λαμβάνει ή ορίζει το ποσό πληρωμής.
Οι έγκυρες τιμές είναι μεταξύ 0.01 και 999,999,999.99.
Τιμή: Το ποσό πληρωμής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Λαμβάνει ή ορίζει το νόμισμα πληρωμής.
Οι έγκυρες τιμές είναι "CHF" και "EUR".
Τιμή: Το νόμισμα πληρωμής.


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Λαμβάνει ή ορίζει το νόμισμα πληρωμής.
Οι έγκυρες τιμές είναι "CHF" και "EUR".
Τιμή: Το νόμισμα πληρωμής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Λαμβάνει ή ορίζει τον αριθμό λογαριασμού του πιστωτή.
Οι αριθμοί λογαριασμών πρέπει να είναι έγκυρα IBAN τραπεζών της Ελβετίας ή του Λιχτενστάιν.
Τα κενά επιτρέπονται στον αριθμό λογαριασμού.
Τιμή: Ο αριθμός λογαριασμού του πιστωτή.


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Λαμβάνει ή ορίζει τον αριθμό λογαριασμού του πιστωτή.
Οι αριθμοί λογαριασμών πρέπει να είναι έγκυρα IBAN τραπεζών της Ελβετίας ή του Λιχτενστάιν.
Τα κενά επιτρέπονται στον αριθμό λογαριασμού.
Τιμή: Ο αριθμός λογαριασμού του πιστωτή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Λαμβάνει ή ορίζει τη διεύθυνση του πιστωτή.
Τιμή: Η διεύθυνση του πιστωτή.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Λαμβάνει ή ορίζει τη διεύθυνση του πιστωτή.
Τιμή: Η διεύθυνση του πιστωτή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Λαμβάνει ή ορίζει την αναφορά πληρωμής του πιστωτή.
Η αναφορά είναι υποχρεωτική για τα SwissQR IBAN, δηλαδή IBAN στην περιοχή CHxx30000xxxxxx
μέχρι CHxx31999xxxxx.
Εάν καθοριστεί, η αναφορά πρέπει να είναι είτε μια έγκυρη αναφορά SwissQR (συμφωνική
με τη μορφή ISR) είτε μια έγκυρη αναφορά πιστωτή σύμφωνα με το ISO 11649 ("RFxxxx").
Και οι δύο μπορεί να περιέχουν κενά για μορφοποίηση.
Τιμή: Η αναφορά πληρωμής του πιστωτή.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Λαμβάνει ή ορίζει την αναφορά πληρωμής του πιστωτή.
Η αναφορά είναι υποχρεωτική για τα SwissQR IBAN, δηλαδή IBAN στην περιοχή CHxx30000xxxxxx
μέχρι CHxx31999xxxxx.
Εάν καθοριστεί, η αναφορά πρέπει να είναι είτε μια έγκυρη αναφορά SwissQR (συμφωνική
με τη μορφή ISR) είτε μια έγκυρη αναφορά πιστωτή σύμφωνα με το ISO 11649 ("RFxxxx").
Και οι δύο μπορεί να περιέχουν κενά για μορφοποίηση.
Τιμή: Η αναφορά πληρωμής του πιστωτή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Λαμβάνει ή ορίζει τη διεύθυνση του οφειλέτη.
Ο οφειλέτης είναι προαιρετικός. Εάν παραλειφθεί, τόσο η ρύθμιση αυτού του πεδίου σε null ή
η ρύθμιση μιας διεύθυνσης με όλες τις τιμές null ή κενές είναι εντάξει.
Τιμή: Η διεύθυνση του οφειλέτη.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Λαμβάνει ή ορίζει τη διεύθυνση του οφειλέτη.
Ο οφειλέτης είναι προαιρετικός. Εάν παραλειφθεί, τόσο η ρύθμιση αυτού του πεδίου σε null ή
η ρύθμιση μιας διεύθυνσης με όλες τις τιμές null ή κενές είναι εντάξει.
Τιμή: Η διεύθυνση του οφειλέτη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Λαμβάνει ή ορίζει το πρόσθετο αδόμητο μήνυμα.
Τιμή: Το αδόμητο μήνυμα.


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Λαμβάνει ή ορίζει το πρόσθετο αδόμητο μήνυμα.
Τιμή: Το αδόμητο μήνυμα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Λαμβάνει ή ορίζει τις πρόσθετες δομημένες πληροφορίες του τιμολογίου.
Τιμή: Οι δομημένες πληροφορίες του τιμολογίου.


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Λαμβάνει ή ορίζει τις πρόσθετες δομημένες πληροφορίες του τιμολογίου.
Τιμή: Οι δομημένες πληροφορίες του τιμολογίου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

