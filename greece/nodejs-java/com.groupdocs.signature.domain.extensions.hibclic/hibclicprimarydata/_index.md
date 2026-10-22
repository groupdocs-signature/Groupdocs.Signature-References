---
title: "HIBCLICPrimaryData"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Κλάση για την αποθήκευση των πρωτογενών δεδομένων του HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
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
| [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Προεπιλεγμένο ctor() |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Καθορίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Καθορίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Καθορίζει τον αριθμό προϊόντος ή καταλόγου. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Καθορίζει τον αριθμό προϊόντος ή καταλόγου. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Καθορίζει το αναγνωριστικό μονάδας μέτρησης. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Καθορίζει το αναγνωριστικό μονάδας μέτρησης. |
| [deepClone()](#deepClone--) | Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου. |
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Προεπιλεγμένο ctor()

### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Καθορίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. Ο κωδικός ταυτοποίησης του ετικετοποιητή πρέπει να είναι αλφαριθμητικό 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα αλφαβητικό.

**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Καθορίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. Ο κωδικός ταυτοποίησης του ετικετοποιητή πρέπει να είναι αλφαριθμητικό 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα αλφαβητικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Καθορίζει τον αριθμό προϊόντος ή καταλόγου. Ο αριθμός προϊόντος ή καταλόγου πρέπει να είναι αλφαριθμητικό έως 18 σύμβολα.

**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Καθορίζει τον αριθμό προϊόντος ή καταλόγου. Ο αριθμός προϊόντος ή καταλόγου πρέπει να είναι αλφαριθμητικό έως 18 σύμβολα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Καθορίζει το αναγνωριστικό μονάδας μέτρησης. Το αναγνωριστικό μονάδας μέτρησης πρέπει να είναι ακέραια τιμή από 0 έως 9.

**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Καθορίζει το αναγνωριστικό μονάδας μέτρησης. Το αναγνωριστικό μονάδας μέτρησης πρέπει να είναι ακέραια τιμή από 0 έως 9.

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
