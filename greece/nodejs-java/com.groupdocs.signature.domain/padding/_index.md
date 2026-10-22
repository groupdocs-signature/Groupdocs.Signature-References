---
title: "Padding"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει τις πληροφορίες γεμίσματος ή περιθωρίου που σχετίζονται με το στοιχείο."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Αντιπροσωπεύει τις πληροφορίες γεμίσματος ή περιθωρίου που σχετίζονται με το στοιχείο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Padding()](#Padding--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Padding χρησιμοποιώντας μηδενικές τιμές. |
| [Padding(int all)](#Padding-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Padding χρησιμοποιώντας το παρεχόμενο μέγεθος περιθωρίου για όλες τις πλευρές. |
| [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Padding χρησιμοποιώντας τα παρεχόμενα μεγέθη περιθωρίων. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Empty](#Empty) | Παρέχει ένα αντικείμενο Padding χωρίς περιθώριο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAll()](#getAll--) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για όλες τις πλευρές. |
| [setAll(int value)](#setAll-int-) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για όλες τις πλευρές. |
| [getLeft()](#getLeft--) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για την αριστερή πλευρά. |
| [setLeft(int value)](#setLeft-int-) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για την αριστερή πλευρά. |
| [getRight()](#getRight--) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για τη δεξιά πλευρά. |
| [setRight(int value)](#setRight-int-) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για τη δεξιά πλευρά. |
| [getTop()](#getTop--) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για την επάνω πλευρά. |
| [setTop(int value)](#setTop-int-) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για την επάνω πλευρά. |
| [getBottom()](#getBottom--) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για την κάτω πλευρά. |
| [setBottom(int value)](#setBottom-int-) | Λαμβάνει ή ορίζει την τιμή περιθωρίου για την κάτω πλευρά. |
| [getHorizontal()](#getHorizontal--) | Λαμβάνει το συνδυασμένο περιθώριο για τις δεξιές και αριστερές πλευρές. |
| [getVertical()](#getVertical--) | Λαμβάνει το συνδυασμένο περιθώριο για τις πάνω και κάτω πλευρές. |
| [deepClone()](#deepClone--) | Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου. |
| [toString()](#toString--) | Παρακάμπτει τη μετατροπή σε συμβολοσειρά |
### Padding() {#Padding--}
```
public Padding()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Padding χρησιμοποιώντας μηδενικές τιμές.

### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Padding χρησιμοποιώντας το παρεχόμενο μέγεθος περιθωρίου για όλες τις πλευρές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όλα | int | Ο αριθμός των μονάδων μέτρησης που θα χρησιμοποιηθούν για το περιθώριο σε όλες τις πλευρές. |

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Padding χρησιμοποιώντας τα παρεχόμενα μεγέθη περιθωρίων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριστερά | int | Το μέγεθος του αριστερού περιθωρίου. |
| δεξιά | int | Το μέγεθος της δεξιάς επένδυσης. |
| επάνω | int | Το μέγεθος της επάνω επένδυσης. |
| κάτω | int | Το μέγεθος της κάτω επένδυσης. |

### Empty {#Empty}
```
public static final Padding Empty
```


Παρέχει ένα αντικείμενο Padding χωρίς περιθώριο.

### getAll() {#getAll--}
```
public final int getAll()
```


Λαμβάνει ή ορίζει την τιμή padding για όλες τις άκρες. Η αλλαγή οποιασδήποτε μερικής άκρης όπως αριστερά ή πάνω θέτει αυτήν την ιδιότητα σε 0;

**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Λαμβάνει ή ορίζει την τιμή padding για όλες τις άκρες. Η αλλαγή οποιασδήποτε μερικής άκρης όπως αριστερά ή πάνω θέτει αυτήν την ιδιότητα σε 0;

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Λαμβάνει ή ορίζει την τιμή περιθωρίου για την αριστερή πλευρά.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Λαμβάνει ή ορίζει την τιμή περιθωρίου για την αριστερή πλευρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Λαμβάνει ή ορίζει την τιμή περιθωρίου για τη δεξιά πλευρά.

**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Λαμβάνει ή ορίζει την τιμή περιθωρίου για τη δεξιά πλευρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Λαμβάνει ή ορίζει την τιμή περιθωρίου για την επάνω πλευρά.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Λαμβάνει ή ορίζει την τιμή περιθωρίου για την επάνω πλευρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Λαμβάνει ή ορίζει την τιμή περιθωρίου για την κάτω πλευρά.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Λαμβάνει ή ορίζει την τιμή περιθωρίου για την κάτω πλευρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Λαμβάνει το συνδυασμένο περιθώριο για τις δεξιές και αριστερές πλευρές.

**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Λαμβάνει το συνδυασμένο περιθώριο για τις πάνω και κάτω πλευρές.

**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου.

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Παρακάμπτει τη μετατροπή σε συμβολοσειρά

**Returns:**
java.lang.String -
