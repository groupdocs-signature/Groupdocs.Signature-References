---
title: "Γωνίες"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αναπαριστά τις γωνίες ενός τετράγωνου γραφικού αντικειμένου."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Αναπαριστά τις γωνίες ενός τετράγωνου γραφικού αντικειμένου.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Corners()](#Corners--) | Αρχικοποιεί μια νέα παρουσία της κλάσης Corners χρησιμοποιώντας μηδενικές τιμές. |
|
|  | [Corners(double all)](#Corners-double-) | Αρχικοποιεί μια νέα παρουσία της κλάσης Corners χρησιμοποιώντας την παρεχόμενη τιμή για όλες τις γωνίες. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Αρχικοποιεί μια νέα παρουσία της κλάσης Corners χρησιμοποιώντας τις παρεχόμενες τιμές. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Empty](#Empty) | Παρέχει ένα αντικείμενο Corners χωρίς δεδομένα. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAll()](#getAll--) | Λαμβάνει ή ορίζει την τιμή για όλες τις γωνίες. |
|
|  | [setAll(double value)](#setAll-double-) | Λαμβάνει ή ορίζει την τιμή για όλες τις γωνίες. |
|
|  | [getTopLeft()](#getTopLeft--) | Λαμβάνει ή ορίζει την τιμή της πάνω αριστερής γωνίας. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | Λαμβάνει ή ορίζει την τιμή της πάνω αριστερής γωνίας. |
|
|  | [getTopRight()](#getTopRight--) | Λαμβάνει ή ορίζει την τιμή της επάνω δεξιάς γωνίας. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | Λαμβάνει ή ορίζει την τιμή της επάνω δεξιάς γωνίας. |
|
|  | [getBottomLeft()](#getBottomLeft--) | Λαμβάνει ή ορίζει την τιμή της κάτω αριστερής γωνίας. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | Λαμβάνει ή ορίζει την τιμή της κάτω αριστερής γωνίας. |
|
|  | [getBottomRight()](#getBottomRight--) | Λαμβάνει ή ορίζει την τιμή της κάτω δεξιάς γωνίας. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | Λαμβάνει ή ορίζει την τιμή της κάτω δεξιάς γωνίας. |
|
|  | [deepClone()](#deepClone--) | Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Αντικατάσταση της μεθόδου equals |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά την απόκτηση μοναδικής τιμής hash code |
|
|  | [toString()](#toString--) | Αντικαθιστά τη μετατροπή σε συμβολοσειρά. |
|
### Corners() {#Corners--}
```
public Corners()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης Corners χρησιμοποιώντας μηδενικές τιμές.


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης Corners χρησιμοποιώντας την παρεχόμενη τιμή για όλες τις γωνίες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όλα | double | Η τιμή που θα χρησιμοποιηθεί για το γέμισμα (padding) όλων των γωνιών. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης Corners χρησιμοποιώντας τις παρεχόμενες τιμές.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | topLeft | double | Τιμή επάνω αριστερής γωνίας. |
|
|  | topRight | double | Τιμή επάνω δεξιάς γωνίας. |
|
|  | bottomLeft | double | Τιμή κάτω αριστερής γωνίας. |
|
|  | bottomRight | double | Τιμή κάτω δεξιάς γωνίας. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


Παρέχει ένα αντικείμενο Corners χωρίς δεδομένα.


### getAll() {#getAll--}
```
public final double getAll()
```


Λαμβάνει ή ορίζει την τιμή για όλες τις γωνίες.
Η αλλαγή οποιασδήποτε μερικής γωνίας, όπως η επάνω δεξιά, θέτει αυτήν την ιδιότητα σε 0.


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Λαμβάνει ή ορίζει την τιμή για όλες τις γωνίες.
Η αλλαγή οποιασδήποτε μερικής γωνίας, όπως η επάνω δεξιά, θέτει αυτήν την ιδιότητα σε 0.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Λαμβάνει ή ορίζει την τιμή της πάνω αριστερής γωνίας.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Λαμβάνει ή ορίζει την τιμή της πάνω αριστερής γωνίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Λαμβάνει ή ορίζει την τιμή της επάνω δεξιάς γωνίας.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Λαμβάνει ή ορίζει την τιμή της επάνω δεξιάς γωνίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Λαμβάνει ή ορίζει την τιμή της κάτω αριστερής γωνίας.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Λαμβάνει ή ορίζει την τιμή της κάτω αριστερής γωνίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Λαμβάνει ή ορίζει την τιμή της κάτω δεξιάς γωνίας.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Λαμβάνει ή ορίζει την τιμή της κάτω δεξιάς γωνίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου.


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Αντικατάσταση της μεθόδου equals


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Παράδειγμα προς σύγκριση. |
|

**Returns:**
boolean - Επιστρέφει true εάν οι ιδιότητες των αντικειμένων είναι ίσες.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Αντικαθιστά την απόκτηση μοναδικής τιμής hash code


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Αντικαθιστά τη μετατροπή σε συμβολοσειρά.


**Returns:**
java.lang.String - 
