---
title: "HIBCLICPrimaryData"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Κλάση για αποθήκευση των πρωτογενών δεδομένων HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 12
url: /el/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Κλάση για αποθήκευση πρωτεύοντων δεδομένων HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Προεπιλεγμένος ctor() |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Αναγνωρίζει την ημερομηνία του κώδικα ταυτοποίησης του ετικετοποιητή. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Αναγνωρίζει την ημερομηνία του κώδικα ταυτοποίησης του ετικετοποιητή. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Αναγνωρίζει προϊόν ή αριθμό καταλόγου. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Αναγνωρίζει προϊόν ή αριθμό καταλόγου. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Αναγνωρίζει το αναγνωριστικό μονάδας μέτρησης. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Αναγνωρίζει το αναγνωριστικό μονάδας μέτρησης. |
|
|  | [deepClone()](#deepClone--) | Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Προεπιλεγμένος ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Αναγνωρίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. Ο κωδικός ταυτοποίησης του ετικετοποιητή πρέπει να είναι αλφαριθμητικό 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα να είναι αλφαβητικός.
να είναι αλφαριθμητικό 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα αλφαβητικό.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Αναγνωρίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. Ο κωδικός ταυτοποίησης του ετικετοποιητή πρέπει να είναι αλφαριθμητικό 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα να είναι αλφαβητικός.
να είναι αλφαριθμητικό 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα αλφαβητικό.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Αναγνωρίζει προϊόν ή αριθμό καταλόγου. Ο αριθμός προϊόντος ή καταλόγου πρέπει να είναι αλφαριθμητικός
συμβολοσειρά έως 18 σύμβολα μήκους.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Αναγνωρίζει προϊόν ή αριθμό καταλόγου. Ο αριθμός προϊόντος ή καταλόγου πρέπει να είναι αλφαριθμητικός
συμβολοσειρά έως 18 σύμβολα μήκους.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Αναγνωρίζει το αναγνωριστικό μονάδας μέτρησης. Το αναγνωριστικό μονάδας μέτρησης πρέπει να είναι ακέραια τιμή από 0 έως 9.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Αναγνωρίζει το αναγνωριστικό μονάδας μέτρησης. Το αναγνωριστικό μονάδας μέτρησης πρέπει να είναι ακέραια τιμή από 0 έως 9.


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
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
