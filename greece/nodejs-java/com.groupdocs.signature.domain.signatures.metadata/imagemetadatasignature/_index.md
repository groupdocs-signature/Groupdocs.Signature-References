---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει τις ιδιότητες της υπογραφής μεταδεδομένων εικόνας."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Περιέχει τις ιδιότητες της υπογραφής μεταδεδομένων εικόνας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Δημιουργεί Image Metadata Signature με Id και τιμή |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getId()](#getId--) | Το αναγνωριστικό του Image Metadata signature. |
| [setId(int value)](#setId-int-) | Το αναγνωριστικό του Image Metadata signature. |
| [getSize()](#getSize--) | Τιμή μόνο για ανάγνωση για λήψη του μεγέθους της τιμής Metadata |
| [setSize(int value)](#setSize-int-) | Τιμή μόνο για ανάγνωση για λήψη του μεγέθους της τιμής Metadata |
| [getDescription()](#getDescription--) | Τιμή μόνο για ανάγνωση για λήψη περιγραφής για τυπική Image Metadata signature |
| [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
| [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
| [deepClone()](#deepClone--) | Κλωνοποιεί την παρουσία του Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Κλωνοποιήστε την παρουσία Image Metadata Signature με την δεδομένη τιμή. |
| [toBoolean()](#toBoolean--) | Μετατρέπει σε boolean. |
| [toInteger()](#toInteger--) | Μετατρέπει σε integer. |
| [toLong()](#toLong--) | Μετατρέπει σε long. |
| [toSingle()](#toSingle--) | Μετατρέπει σε float. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Μετατρέπει σε float. |
| [toDouble()](#toDouble--) | Μετατρέπει σε Double. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Μετατρέπει σε Double. |
| [toDecimal()](#toDecimal--) | Μετατρέπει σε Decimal. |
| [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Μετατρέπει σε Decimal. |
| [toDateTime()](#toDateTime--) | Μετατρέπει σε DateTime. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Μετατρέπει σε DateTime. |
| [toString()](#toString--) | Μετατρέπει σε String με την υπερφόρτωση της μεθόδου ToString() |
| [toString(String format)](#toString-java.lang.String-) | Μετατρέπει σε String με καθορισμένη μορφή |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Μετατρέπει σε String με καθορισμένη μορφή |
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


Δημιουργεί Image Metadata Signature με Id και τιμή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | int | Μοναδικό αναγνωριστικό του ονόματος Image Metadata Signature. Δείτε τις αναφορές για τις προδιαγραφές ετικετών Exif για πιθανές τιμές id. |
| τιμή | java.lang.Object | Τιμή μεταδεδομένων |

### getId() {#getId--}
```
public final int getId()
```


Το αναγνωριστικό του Image Metadata signature. Δείτε την κλάση [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) που περιέχει τυπική Signature με προκαθορισμένη τιμή Id.

**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Το αναγνωριστικό του Image Metadata signature. Δείτε την κλάση [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) που περιέχει τυπική Signature με προκαθορισμένη τιμή Id.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Τιμή μόνο για ανάγνωση για λήψη του μεγέθους της τιμής Metadata

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Τιμή μόνο για ανάγνωση για λήψη του μεγέθους της τιμής Metadata

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Τιμή μόνο για ανάγνωση για λήψη περιγραφής για τυπική Image Metadata signature

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
| υπογραφή | java.lang.Object | Αντικείμενο υπογραφής για σύγκριση. |

**Returns:**
boolean - Επιστρέφει true εάν το δοσμένο αντικείμενο υπογραφής έχει τον ίδιο τύπο και όλες οι ιδιότητές του είναι ίσες με τις ιδιότητες αυτού του αντικειμένου.
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


Κλωνοποιεί την παρουσία του Metadata Signature.

**Returns:**
java.lang.Object - Επιστρέφει την κλωνοποιημένη παρουσία του Metadata Signature
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Κλωνοποιήστε την παρουσία Image Metadata Signature με την δεδομένη τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object | Τιμή για το νέο κλωνοποιημένο αντικείμενο. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Μετατρέπει σε boolean.

**Returns:**
boolean - Επιστρέφει την τιμή υπογραφής Metadata ως boolean.

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί.
### toInteger() {#toInteger--}
```
public int toInteger()
```


Μετατρέπει σε integer.

**Returns:**
int - Επιστρέφει την τιμή υπογραφής Metadata ως ακέραιο.

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί.
### toLong() {#toLong--}
```
public final long toLong()
```


Μετατρέπει σε long.

**Returns:**
long - Επιστρέφει την τιμή Metadata Signature ως long.

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί.
### toSingle() {#toSingle--}
```
public final float toSingle()
```


Μετατρέπει σε float.

**Returns:**
float - Επιστρέφει την τιμή Image Metadata Signature ως float.

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι βασισμένη σε συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture.
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Μετατρέπει σε float.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πάροχος | java.util.Locale | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί |

**Returns:**
float - Επιστρέφει την τιμή υπογραφής Metadata ως float.
### toDouble() {#toDouble--}
```
public double toDouble()
```


Μετατρέπει σε Double.

**Returns:**
double - Επιστρέφει την τιμή Image Metadata Signature ως Double.

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι βασισμένη σε συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture.
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Μετατρέπει σε Double.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πάροχος | java.util.Locale | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί |

**Returns:**
double - Επιστρέφει την τιμή υπογραφής Metadata ως Double.
### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Μετατρέπει σε Decimal.

**Returns:**
java.math.BigDecimal - Επιστρέφει την τιμή Image Metadata Signature ως Decimal.

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι βασισμένη σε συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture.
### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Μετατρέπει σε Decimal.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πάροχος | java.util.Locale | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί |

**Returns:**
java.math.BigDecimal - Επιστρέφει την τιμή Metadata Signature ως Decimal.
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Μετατρέπει σε DateTime.

**Returns:**
java.util.Date - Επιστρέφει την τιμή υπογραφής Metadata ως DateTime.

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί. Εάν η αρχική τιμή είναι βασισμένη σε συμβολοσειρά, θα χρησιμοποιηθεί η προεπιλεγμένη πληροφορία πολιτισμού από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture.
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Μετατρέπει σε DateTime.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πάροχος | java.util.Locale | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

--------------------

Αναφέρει εξαίρεση εάν η τιμή Metadata δεν μπορεί να μετατραπεί |

**Returns:**
java.util.Date - Επιστρέφει την τιμή υπογραφής Metadata ως DateTime.
### toString() {#toString--}
```
public String toString()
```


Μετατρέπει σε String με την υπερφόρτωση της μεθόδου ToString()

**Returns:**
java.lang.String - Επιστρέφει την τιμή υπογραφής Metadata ως String.
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Μετατρέπει σε String με καθορισμένη μορφή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μορφή | java.lang.String | Συμβολοσειρά μορφής δεδομένων. |

--------------------

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False". Η προεπιλεγμένη πληροφορία πολιτισμού θα χρησιμοποιηθεί από τις ιδιότητες SignatureSettings, SignatureSettings.DefaultCulture |

**Returns:**
java.lang.String - Επιστρέφει την τιμή υπογραφής Metadata ως String.
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Μετατρέπει σε String με καθορισμένη μορφή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | java.lang.String | Συμβολοσειρά μορφής δεδομένων. |
|  | πάροχος | java.util.Locale | Πάροχος μορφοποίησης δεδομένων για χρήση με λειτουργίες μετατροπής δεδομένων. |

--------------------

Μετατρέπει μια ιδιότητα boolean σε "True" ή "False" |

**Returns:**
java.lang.String - Επιστρέφει την τιμή υπογραφής Metadata ως String.
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

