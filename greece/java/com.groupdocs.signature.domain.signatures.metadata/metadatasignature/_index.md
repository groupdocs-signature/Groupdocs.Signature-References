---
title: "MetadataSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες υπογραφής μεταδεδομένων."
type: docs
weight: 12
url: /el/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Περιέχει ιδιότητες υπογραφής μεταδεδομένων.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Καθορίζει μοναδικό όνομα μεταδεδομένων. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Καθορίζει μοναδικό όνομα μεταδεδομένων. |
|
|  | [getValue()](#getValue--) | Καθορίζει αντικείμενο μεταδεδομένων. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Καθορίζει αντικείμενο μεταδεδομένων. |
|
|  | [getType()](#getType--) | Καθορίζει τύπο τιμής μεταδεδομένων. |
|
|  | [setType(int value)](#setType-int-) | Καθορίζει τύπο τιμής μεταδεδομένων. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Λαμβάνει ή ορίζει την υλοποίηση του interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων Value της υπογραφής. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Λαμβάνει ή ορίζει την υλοποίηση του interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων Value της υπογραφής. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Αποκτήστε το αντικείμενο από τη τιμή Metadata Signature κατά την απο-σειριοποίηση. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Αποκτήστε το αντικείμενο από το κείμενο Metadata Signature κατά την απο-σειριοποίηση. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
|  | [toBoolean()](#toBoolean--) | Μετατρέπει σε boolean. |
|
|  | [toInteger()](#toInteger--) | Μετατρέπει σε integer. |
|
|  | [toDouble()](#toDouble--) | Μετατρέπει σε Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Μετατρέπει σε Double. |
|
|  | [toSingle()](#toSingle--) | Μετατρέπει σε float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Μετατρέπει σε float. |
|
|  | [toDateTime()](#toDateTime--) | Μετατρέπει σε DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Μετατρέπει σε DateTime. |
|
|  | [toString()](#toString--) | Μετατρέπει σε String με την υπερκαθορισμένη μέθοδο ToString() |
|
|  | [toString(String format)](#toString-java.lang.String-) | Μετατρέπει σε String με καθορισμένη μορφή |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Μετατρέπει σε String με καθορισμένη μορφή |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιεί το στιγμιότυπο της Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Κλωνοποιεί το αντικείμενο Metadata Signature με την δεδομένη τιμή. |
|
### getName() {#getName--}
```
public final String getName()
```


Καθορίζει μοναδικό όνομα μεταδεδομένων.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Καθορίζει μοναδικό όνομα μεταδεδομένων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Καθορίζει αντικείμενο μεταδεδομένων.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Καθορίζει αντικείμενο μεταδεδομένων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Καθορίζει τύπο τιμής μεταδεδομένων.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Καθορίζει τύπο τιμής μεταδεδομένων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Λαμβάνει ή ορίζει την υλοποίηση του interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων Value της υπογραφής.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Λαμβάνει ή ορίζει την υλοποίηση του interface [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση των ιδιοτήτων Value της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Αποκτήστε το αντικείμενο από τη τιμή Metadata Signature κατά την απο-σειριοποίηση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - Αντικείμενο τύπου T


T
: Τύπος αντικειμένου για αποανασυσκευασία από την τιμή Metadata

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Αποκτήστε το αντικείμενο από το κείμενο Metadata Signature κατά την απο-σειριοποίηση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Ορίστε προσαρμοσμένη υλοποίηση κρυπτογράφησης δεδομένων |


T
: Τύπος αντικειμένου για αποανασυσκευασία από την τιμή Metadata
|

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | υπογραφή | java.lang.Object | Αντικείμενο υπογραφής για σύγκριση. |
|

**Returns:**
boolean - Επιστρέφει true εάν το περασμένο αντικείμενο υπογραφής έχει τον ίδιο τύπο και όλες οι ιδιότητές του είναι ίσες με τις ιδιότητες αυτού του αντικειμένου.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Αντικαθιστά τη μέθοδο GetHashCode


**Returns:**
int - Κώδικας κατακερματισμού υπογραφής

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Μετατρέπει σε boolean.


**Returns:**
boolean - Επιστρέφει την τιμή της υπογραφής Metadata ως boolean.

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


Μετατρέπει σε integer.


**Returns:**
int - Επιστρέφει την τιμή της υπογραφής Metadata ως ακέραιο.

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί.

<br />


### toDouble() {#toDouble--}
```
public double toDouble()
```


Μετατρέπει σε Double.


**Returns:**
double - Επιστρέφει την τιμή της υπογραφής Metadata ως Double.

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture.

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Μετατρέπει σε Double.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πάροχος | java.util.Locale | Πάροχος μορφοποίησης δεδομένων για χρήση σε λειτουργίες μετατροπής δεδομένων. |

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί

<br />

|

**Returns:**
double - Επιστρέφει την τιμή της υπογραφής Metadata ως Double.

### toSingle() {#toSingle--}
```
public float toSingle()
```


Μετατρέπει σε float.


**Returns:**
float - Επιστρέφει την τιμή της υπογραφής Metadata ως float.

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture ().

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
```


Μετατρέπει σε float.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πάροχος | java.util.Locale | Πάροχος μορφοποίησης δεδομένων για χρήση σε λειτουργίες μετατροπής δεδομένων. |

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί

<br />

|

**Returns:**
float - Επιστρέφει την τιμή της υπογραφής Metadata ως float.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Μετατρέπει σε DateTime.


**Returns:**
java.util.Date - Επιστρέφει την τιμή της υπογραφής Metadata ως DateTime.

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture.

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Μετατρέπει σε DateTime.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πάροχος | java.util.Locale | Πάροχος μορφοποίησης δεδομένων για χρήση σε λειτουργίες μετατροπής δεδομένων. |

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί

<br />

|

**Returns:**
java.util.Date - Επιστρέφει την τιμή της υπογραφής Metadata ως DateTime.

### toString() {#toString--}
```
public String toString()
```


Μετατρέπει σε String με την υπερκαθορισμένη μέθοδο ToString()


**Returns:**
java.lang.String - Επιστρέφει την τιμή της υπογραφής Metadata ως String.

<br />

*** ** * ** ***

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False". Για άλλου τύπου δεδομένα θα χρησιμοποιηθεί ο προεπιλεγμένος πάροχος μορφοποίησης δεδομένων.

<br />


### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Μετατρέπει σε String με καθορισμένη μορφή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μορφή | java.lang.String | Συμβολοσειρά μορφής δεδομένων. |

<br />

*** ** * ** ***

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False". Θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture.

<br />

|

**Returns:**
java.lang.String - Επιστρέφει την τιμή της υπογραφής Metadata ως String.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Μετατρέπει σε String με καθορισμένη μορφή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μορφή | java.lang.String | Συμβολοσειρά μορφής δεδομένων. |
|
|  | πάροχος | java.util.Locale | Πάροχος μορφοποίησης δεδομένων για χρήση σε λειτουργίες μετατροπής δεδομένων. |

<br />

*** ** * ** ***

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False".

<br />

|

**Returns:**
java.lang.String - Επιστρέφει την τιμή της υπογραφής Metadata ως String.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Κλωνοποιεί το στιγμιότυπο της Metadata Signature.


**Returns:**
java.lang.Object - Επιστρέφει κλωνοποιημένο αντικείμενο Metadata Signature

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Κλωνοποιεί το αντικείμενο Metadata Signature με την δεδομένη τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.Object | Τιμή για νέο κλωνοποιημένο αντικείμενο. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

