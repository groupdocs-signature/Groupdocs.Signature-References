---
title: "Mailmark2D"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στο Royal Mail 2D Mailmark."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στο Royal Mail 2D Mailmark.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | Δημιουργεί συνδυασμένα δεδομένα Royal Mail Mailmark με προεπιλεγμένες τιμές πρωτεύοντων και δευτερευόντων δεδομένων. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | Αναγνωρίζει το φορτίο barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Αναγνωρίζει το φορτίο barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. |
|
|  | [getVersionID()](#getVersionID--) | Αναγνωρίζει την έκδοση του barcode όπως είναι σχετική με κάθε Information Type ID. |
|
|  | [getClass_()](#getClass---) | Αναγνωρίζει την κλάση του αντικειμένου. |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | Αναγνωρίζει την κλάση του αντικειμένου. |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. |
|
|  | [getItemID()](#getItemID--) | Αναγνωρίζει το μοναδικό αντικείμενο εντός του Supply Chain ID. |
|
|  | [setItemID(int value)](#setItemID-int-) | Αναγνωρίζει το μοναδικό αντικείμενο εντός του Supply Chain ID. |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS |
Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων.
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS |
Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων.
|
|  | [getRTSFlag()](#getRTSFlag--) | Σημαία που υποδεικνύει ποιο επίπεδο της υπηρεσίας Return to Sender ζητείται. |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Σημαία που υποδεικνύει ποιο επίπεδο της υπηρεσίας Return to Sender ζητείται. |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Περιέχει τον κωδικό αλληλογραφίας Return to Sender αλλά χωρίς DPS. |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Περιέχει τον κωδικό αλληλογραφίας Return to Sender αλλά χωρίς DPS. |
|
|  | [getCustomerContent()](#getCustomerContent--) | Προαιρετικός χώρος για χρήση από τον πελάτη. |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Προαιρετικός χώρος για χρήση από τον πελάτη. |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Λειτουργία κωδικοποίησης του barcode DataMatrix. |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Λειτουργία κωδικοποίησης του barcode DataMatrix. |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
|
|  | [deepClone()](#deepClone--) | Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου. |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Δημιουργεί συνδυασμένα δεδομένα Royal Mail Mailmark με προεπιλεγμένες τιμές πρωτεύοντων και δευτερευόντων δεδομένων.


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες.


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Αναγνωρίζει το φορτίο barcode Royal Mail Mailmark για κάθε τύπο προϊόντος.

<br />

*** ** * ** ***

Έγκυρες τιμές: "0" - Ενδοχώριες ταξινομημένες και αταξινόμητες "A" - Ηλεκτρονική ταχυδρομική αποστολή "B" - Σφραγισμός "C" - Συγκέντρωση

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Αναγνωρίζει το φορτίο barcode Royal Mail Mailmark για κάθε τύπο προϊόντος.

<br />

*** ** * ** ***

Έγκυρες τιμές: "0" - Ενδοχώριες ταξινομημένες και αταξινόμητες "A" - Ηλεκτρονική ταχυδρομική αποστολή "B" - Σφραγισμός "C" - Συγκέντρωση

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Αναγνωρίζει την έκδοση του barcode όπως είναι σχετική με κάθε Information Type ID.

<br />

*** ** * ** ***

Έγκυρες τιμές: "1" - αυτή τη στιγμή χρησιμοποιείται μόνο αυτή η τιμή (προεπιλογή) "0" και "2" έως "9" και "A" έως "Z" εφεδρικές, κρατημένες για πιθανή μελλοντική χρήση.

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Αναγνωρίζει την κλάση του αντικειμένου.

<br />

*** ** * ** ***

Έγκυρες τιμές: "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - Economy (Λιανική) "5" - Deferred (Λιανική) "8" - Premium (Πρόσβαση Δικτύου) "9" - Standard (Πρόσβαση Δικτύου)

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Αναγνωρίζει την κλάση του αντικειμένου.

<br />

*** ** * ** ***

Έγκυρες τιμές: "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - Economy (Λιανική) "5" - Deferred (Λιανική) "8" - Premium (Πρόσβαση Δικτύου) "9" - Standard (Πρόσβαση Δικτύου)

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή.
Μέγιστη τιμή: 9999999.


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή.
Μέγιστη τιμή: 9999999.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Αναγνωρίζει το μοναδικό αντικείμενο εντός του Supply Chain ID.
Κάθε barcode Mailmark πρέπει να φέρει ένα ID ώστε να μπορεί να ταυτοποιηθεί μοναδικά για τουλάχιστον 90 ημέρες.
Μέγιστη τιμή: 99999999.


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Αναγνωρίζει το μοναδικό αντικείμενο εντός του Supply Chain ID.
Κάθε barcode Mailmark πρέπει να φέρει ένα ID ώστε να μπορεί να ταυτοποιηθεί μοναδικά για τουλάχιστον 90 ημέρες.
Μέγιστη τιμή: 99999999.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS
Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων.
Περιοχή (1 ή 2 χαρακτήρες)
Περιφέρεια(1 ή 2 χαρακτήρες)
Τομέας(1 χαρακτήρας)
Μονάδα(2 χαρακτήρες)
DPS (2 χαρακτήρες).
Ο Ταχυδρομικός κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®. Το μέγιστο μήκος είναι 9.


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS
Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων.
Περιοχή (1 ή 2 χαρακτήρες)
Περιφέρεια(1 ή 2 χαρακτήρες)
Τομέας(1 χαρακτήρας)
Μονάδα(2 χαρακτήρες)
DPS (2 χαρακτήρες).
Ο Ταχυδρομικός κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®. Το μέγιστο μήκος είναι 9.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Σημαία που υποδεικνύει ποιο επίπεδο της υπηρεσίας Return to Sender ζητείται. Το μέγιστο μήκος είναι 1.


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Σημαία που υποδεικνύει ποιο επίπεδο της υπηρεσίας Return to Sender ζητείται. Το μέγιστο μήκος είναι 1.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Περιέχει τον κωδικό αλληλογραφίας Return to Sender αλλά χωρίς DPS.
Ο κωδικός PC (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®.


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Περιέχει τον κωδικό αλληλογραφίας Return to Sender αλλά χωρίς DPS.
Ο κωδικός PC (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Προαιρετικός χώρος για χρήση από τον πελάτη.

<br />

*** ** * ** ***

Μέγιστο μήκος ανά τύπο [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Τύπος 7: 6 χαρακτήρες Τύπος 9: 45 χαρακτήρες Τύπος 29: 25 χαρακτήρες

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Προαιρετικός χώρος για χρήση από τον πελάτη.

<br />

*** ** * ** ***

Μέγιστο μήκος ανά τύπο [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Τύπος 7: 6 χαρακτήρες Τύπος 9: 45 χαρακτήρες Τύπος 29: 25 χαρακτήρες

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Λειτουργία κωδικοποίησης του barcode DataMatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Λειτουργία κωδικοποίησης του barcode DataMatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix.


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου.


**Returns:**
java.lang.Object
