---
title: "ImageMetadataSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες υπογραφής μεταδεδομένων εικόνας."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Περιέχει ιδιότητες υπογραφής μεταδεδομένων εικόνας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Δημιουργεί υπογραφή μεταδεδομένων εικόνας με αναγνωριστικό και τιμή |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getId()](#getId--) | Το αναγνωριστικό της υπογραφής μεταδεδομένων εικόνας. |
|
|  | [setId(int value)](#setId-int-) | Το αναγνωριστικό της υπογραφής μεταδεδομένων εικόνας. |
|
|  | [getSize()](#getSize--) | Τιμή μόνο για ανάγνωση για λήψη του μεγέθους της τιμής των μεταδεδομένων |
|
|  | [setSize(int value)](#setSize-int-) | Τιμή μόνο για ανάγνωση για λήψη του μεγέθους της τιμής των μεταδεδομένων |
|
|  | [getDescription()](#getDescription--) | Τιμή μόνο για ανάγνωση για λήψη της περιγραφής της τυπικής υπογραφής μεταδεδομένων εικόνας |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιεί το στιγμιότυπο της Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Κλωνοποιεί το αντίτυπο της υπογραφής μεταδεδομένων εικόνας με την δοθείσα τιμή. |
|
|  | [toBoolean()](#toBoolean--) | Μετατρέπει σε boolean. |
|
|  | [toInteger()](#toInteger--) | Μετατρέπει σε integer. |
|
|  | [toLong()](#toLong--) | Μετατρέπει σε long. |
|
|  | [toSingle()](#toSingle--) | Μετατρέπει σε float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Μετατρέπει σε float. |
|
|  | [toDouble()](#toDouble--) | Μετατρέπει σε Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Μετατρέπει σε Double. |
|
|  | [toDecimal()](#toDecimal--) | Μετατρέπει σε Decimal. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Μετατρέπει σε Decimal. |
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
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Δημιουργεί υπογραφή μεταδεδομένων εικόνας με αναγνωριστικό και τιμή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αναγνωριστικό | int | Μοναδικό αναγνωριστικό του ονόματος υπογραφής εικόνας μεταδεδομένων. Δείτε τις αναφορές για τις προδιαγραφές ετικετών Exif για τις πιθανές τιμές αναγνωριστικού |
|
|  | τιμή | java.lang.Object | Τιμή μεταδεδομένων |
|

### getId() {#getId--}
```
public final int getId()
```


Το αναγνωριστικό της υπογραφής μεταδεδομένων εικόνας.
Δείτε την κλάση [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) που περιέχει τυπική υπογραφή με προεπιλεγμένη τιμή Id.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Το αναγνωριστικό της υπογραφής μεταδεδομένων εικόνας.
Δείτε την κλάση [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) που περιέχει τυπική υπογραφή με προεπιλεγμένη τιμή Id.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Τιμή μόνο για ανάγνωση για λήψη του μεγέθους της τιμής των μεταδεδομένων


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Τιμή μόνο για ανάγνωση για λήψη του μεγέθους της τιμής των μεταδεδομένων


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Τιμή μόνο για ανάγνωση για λήψη της περιγραφής της τυπικής υπογραφής μεταδεδομένων εικόνας


**Returns:**
java.lang.String
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


Κλωνοποιεί το αντίτυπο της υπογραφής μεταδεδομένων εικόνας με την δοθείσα τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.Object | Τιμή για νέο κλωνοποιημένο αντικείμενο. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

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


### toLong() {#toLong--}
```
public final long toLong()
```


Μετατρέπει σε long.


**Returns:**
long - Επιστρέφει την τιμή της υπογραφής μεταδεδομένων ως long.

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


Μετατρέπει σε float.


**Returns:**
float - Επιστρέφει την τιμή της υπογραφής μεταδεδομένων εικόνας ως float.

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture.

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
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

### toDouble() {#toDouble--}
```
public double toDouble()
```


Μετατρέπει σε Double.


**Returns:**
double - Επιστρέφει την τιμή της υπογραφής μεταδεδομένων εικόνας ως Double.

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

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Μετατρέπει σε Decimal.


**Returns:**
java.math.BigDecimal - Επιστρέφει την τιμή της υπογραφής μεταδεδομένων εικόνας ως Decimal.

<br />

*** ** * ** ***

Εκτοπίζει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture.

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Μετατρέπει σε Decimal.


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
java.math.BigDecimal - Επιστρέφει την τιμή της υπογραφής μεταδεδομένων ως Decimal.

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

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

