---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Κλάση για την αποθήκευση των δευτερευόντων και πρόσθετων δεδομένων του HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Κλάση για αποθήκευση δευτερευόντων και πρόσθετων δεδομένων HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Προεπιλεγμένο ctor() |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Καθορίζει τη μορφή ημερομηνίας λήξης. |
| [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Καθορίζει τη μορφή ημερομηνίας λήξης. |
| [getExpiryDate()](#getExpiryDate--) | Καθορίζει την ημερομηνία λήξης. |
| [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Καθορίζει την ημερομηνία λήξης. |
| [getLotNumber()](#getLotNumber--) | Αναγνωρίζει αριθμό παρτίδας ή δέσμης. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Αναγνωρίζει αριθμό παρτίδας ή δέσμης. |
| [getSerialNumber()](#getSerialNumber--) | Αναγνωρίζει σειριακό αριθμό. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Αναγνωρίζει σειριακό αριθμό. |
| [getDateOfManufacture()](#getDateOfManufacture--) | Αναγνωρίζει ημερομηνία κατασκευής. |
| [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Αναγνωρίζει ημερομηνία κατασκευής. |
| [getQuantity()](#getQuantity--) | Αναγνωρίζει ποσότητα, πρέπει να είναι ακέραιη τιμή από 0 έως 500. |
| [setQuantity(int value)](#setQuantity-int-) | Αναγνωρίζει ποσότητα, πρέπει να είναι ακέραιη τιμή από 0 έως 500. |
| [getLinkCharacter()](#getLinkCharacter--) | Αναγνωρίζει χαρακτήρα σύνδεσης στη συμβολοσειρά εξόδου. |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | Αναγνωρίζει χαρακτήρα σύνδεσης στη συμβολοσειρά εξόδου. |
| [deepClone()](#deepClone--) | Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου. |
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Προεπιλεγμένο ctor()

### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Καθορίζει τη μορφή ημερομηνίας λήξης.

**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Καθορίζει τη μορφή ημερομηνίας λήξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Αναγνωρίζει ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν έχει οριστεί σε None.

**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Αναγνωρίζει ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν έχει οριστεί σε None.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Αναγνωρίζει αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητική συμβολοσειρά με μήκος έως 18 σύμβολα.

**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Αναγνωρίζει αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητική συμβολοσειρά με μήκος έως 18 σύμβολα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Αναγνωρίζει σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά με μήκος έως 18 σύμβολα.

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Αναγνωρίζει σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά με μήκος έως 18 σύμβολα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Αναγνωρίζει ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: DateTime.MinValue

**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Αναγνωρίζει ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: DateTime.MinValue

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Αναγνωρίζει ποσότητα, πρέπει να είναι ακέραιη τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: -1

**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Αναγνωρίζει ποσότητα, πρέπει να είναι ακέραιη τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: -1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Αναγνωρίζει χαρακτήρα σύνδεσης στη συμβολοσειρά εξόδου.

**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Αναγνωρίζει χαρακτήρα σύνδεσης στη συμβολοσειρά εξόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου.

**Returns:**
java.lang.Object
