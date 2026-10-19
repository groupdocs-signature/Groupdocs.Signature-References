---
title: "SwissAddress"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει τη διεύθυνση του πιστωτή ή του οφειλέτη."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Αντιπροσωπεύει τη διεύθυνση του πιστωτή ή του οφειλέτη.
Μπορείτε είτε να ορίσετε οδό, αριθμό σπιτιού, ταχυδρομικό κώδικα και πόλη (τύπος δομημένης διεύθυνσης)
ή γραμμή διεύθυνσης 1 και 2 (τύπος συνδυασμένων στοιχείων διεύθυνσης).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Αποκτά ή ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου ή |
το όνομα της εταιρείας νομικού προσώπου.
|
|  | [setName(String value)](#setName-java.lang.String-) | Αποκτά ή ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου ή |
το όνομα της εταιρείας νομικού προσώπου.
|
|  | [getAddressLine1()](#getAddressLine1--) | Αποκτά ή ορίζει τη γραμμή διεύθυνσης 1. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Αποκτά ή ορίζει τη γραμμή διεύθυνσης 1. |
|
|  | [getAddressLine2()](#getAddressLine2--) | Αποκτά ή ορίζει τη γραμμή διεύθυνσης 2. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Αποκτά ή ορίζει τη γραμμή διεύθυνσης 2. |
|
|  | [getStreet()](#getStreet--) | Αποκτά ή ορίζει το δρόμο. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | Αποκτά ή ορίζει το δρόμο. |
|
|  | [getHouseNo()](#getHouseNo--) | Αποκτά ή ορίζει τον αριθμό σπιτιού. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Αποκτά ή ορίζει τον αριθμό σπιτιού. |
|
|  | [getPostalCode()](#getPostalCode--) | Αποκτά ή ορίζει τον ταχυδρομικό κώδικα. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Αποκτά ή ορίζει τον ταχυδρομικό κώδικα. |
|
|  | [getTown()](#getTown--) | Αποκτά ή ορίζει την πόλη ή το κωμόπολη. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | Αποκτά ή ορίζει την πόλη ή το κωμόπολη. |
|
|  | [getCountryCode()](#getCountryCode--) | Αποκτά ή ορίζει τον διψήφιο κωδικό χώρας ISO. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Αποκτά ή ορίζει τον διψήφιο κωδικό χώρας ISO. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Αποκτά ή ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου ή
το όνομα της εταιρείας νομικού προσώπου.
Τιμή: Το όνομα.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Αποκτά ή ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου ή
το όνομα της εταιρείας νομικού προσώπου.
Τιμή: Το όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Αποκτά ή ορίζει τη γραμμή διεύθυνσης 1.
Η γραμμή διεύθυνσης 1 περιέχει το όνομα του δρόμου, τον αριθμό σπιτιού ή τη θυρίδα ταχυδρομείου.
Αυτό το πεδίο χρησιμοποιείται μόνο για συνδυασμένες διευθύνσεις στοιχείων και είναι προαιρετικό.
Τιμή: Η γραμμή διεύθυνσης 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Αποκτά ή ορίζει τη γραμμή διεύθυνσης 1.
Η γραμμή διεύθυνσης 1 περιέχει το όνομα του δρόμου, τον αριθμό σπιτιού ή τη θυρίδα ταχυδρομείου.
Αυτό το πεδίο χρησιμοποιείται μόνο για συνδυασμένες διευθύνσεις στοιχείων και είναι προαιρετικό.
Τιμή: Η γραμμή διεύθυνσης 1.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Αποκτά ή ορίζει τη γραμμή διεύθυνσης 2.
Η γραμμή διεύθυνσης 2 περιέχει τον ταχυδρομικό κώδικα και την πόλη.
Αυτό το πεδίο χρησιμοποιείται μόνο για συνδυασμένες διευθύνσεις στοιχείων. Για αυτόν τον τύπο, είναι υποχρεωτικό.
Τιμή: Η γραμμή διεύθυνσης 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Αποκτά ή ορίζει τη γραμμή διεύθυνσης 2.
Η γραμμή διεύθυνσης 2 περιέχει τον ταχυδρομικό κώδικα και την πόλη.
Αυτό το πεδίο χρησιμοποιείται μόνο για συνδυασμένες διευθύνσεις στοιχείων. Για αυτόν τον τύπο, είναι υποχρεωτικό.
Τιμή: Η γραμμή διεύθυνσης 2.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Αποκτά ή ορίζει το δρόμο.
Ο δρόμος πρέπει να καθορίζεται χωρίς αριθμό σπιτιού.
Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.
Τιμή: Ο δρόμος.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Αποκτά ή ορίζει το δρόμο.
Ο δρόμος πρέπει να καθορίζεται χωρίς αριθμό σπιτιού.
Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.
Τιμή: Ο δρόμος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Αποκτά ή ορίζει τον αριθμό σπιτιού.
Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.
Τιμή: Ο αριθμός σπιτιού.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Αποκτά ή ορίζει τον αριθμό σπιτιού.
Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.
Τιμή: Ο αριθμός σπιτιού.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Αποκτά ή ορίζει τον ταχυδρομικό κώδικα.
Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.
Τιμή: Ο ταχυδρομικός κώδικας.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Αποκτά ή ορίζει τον ταχυδρομικό κώδικα.
Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.
Τιμή: Ο ταχυδρομικός κώδικας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Αποκτά ή ορίζει την πόλη ή το κωμόπολη.
Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.
Τιμή: Η πόλη ή το κωμόπολη.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Αποκτά ή ορίζει την πόλη ή το κωμόπολη.
Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.
Τιμή: Η πόλη ή το κωμόπολη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Αποκτά ή ορίζει τον διψήφιο κωδικό χώρας ISO.
Ο κωδικός χώρας είναι υποχρεωτικός εκτός εάν ολόκληρη η διεύθυνση περιέχει τιμές null ή κενές.
Τιμή: Ο κωδικός χώρας ISO.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Αποκτά ή ορίζει τον διψήφιο κωδικό χώρας ISO.
Ο κωδικός χώρας είναι υποχρεωτικός εκτός εάν ολόκληρη η διεύθυνση περιέχει τιμές null ή κενές.
Τιμή: Ο κωδικός χώρας ISO.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

