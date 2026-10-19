---
title: "PdfDigitalSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες ψηφιακής υπογραφής PDF."
type: docs
weight: 15
url: /el/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Περιέχει ιδιότητες ψηφιακής υπογραφής PDF.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | Αρχικοποιήστε το Pdf Digital Signature χωρίς πιστοποιητικό. |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Δημιουργήστε το Pdf Digital signature με το καθορισμένο πιστοποιητικό. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | Πληροφορίες που παρέχονται από τον υπογράφοντα για να επιτρέψουν στον παραλήπτη να επικοινωνήσει με τον υπογράφοντα |
για την επαλήθευση της υπογραφής, π.χ.
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Πληροφορίες που παρέχονται από τον υπογράφοντα για να επιτρέψουν στον παραλήπτη να επικοινωνήσει με τον υπογράφοντα |
για την επαλήθευση της υπογραφής, π.χ.
|
|  | [getLocation()](#getLocation--) | Το όνομα κεντρικού υπολογιστή CPU ή η φυσική τοποθεσία της υπογραφής. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Το όνομα κεντρικού υπολογιστή CPU ή η φυσική τοποθεσία της υπογραφής. |
|
|  | [getReason()](#getReason--) | Ο λόγος για την υπογραφή, όπως (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Ο λόγος για την υπογραφή, όπως (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [getType()](#getType--) | Τύπος του Pdf digital signature. |
|
|  | [setType(int value)](#setType-int-) | Τύπος του Pdf digital signature. |
|
|  | [getTimeStamp()](#getTimeStamp--) | Χρονική σήμανση για το Pdf digital signature. |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Χρονική σήμανση για το Pdf digital signature. |
|
|  | [getShowProperties()](#getShowProperties--) | Εξαναγκάστε την εμφάνιση/απόκρυψη των ιδιοτήτων της υπογραφής. |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | Εξαναγκάστε την εμφάνιση/απόκρυψη των ιδιοτήτων της υπογραφής. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιήστε την παρουσία Barcode Signature. |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Αρχικοποιήστε το Pdf Digital Signature χωρίς πιστοποιητικό.


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Δημιουργήστε το Pdf Digital signature με το καθορισμένο πιστοποιητικό.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πιστοποιητικό | java.security.KeyStore | Πιστοποιητικό X509. |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Πληροφορίες που παρέχονται από τον υπογράφοντα για να επιτρέψουν στον παραλήπτη να επικοινωνήσει με τον υπογράφοντα
για την επαλήθευση της υπογραφής, π.χ. έναν αριθμό τηλεφώνου.


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Πληροφορίες που παρέχονται από τον υπογράφοντα για να επιτρέψουν στον παραλήπτη να επικοινωνήσει με τον υπογράφοντα
για την επαλήθευση της υπογραφής, π.χ. έναν αριθμό τηλεφώνου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Το όνομα κεντρικού υπολογιστή CPU ή η φυσική τοποθεσία της υπογραφής.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Το όνομα κεντρικού υπολογιστή CPU ή η φυσική τοποθεσία της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Ο λόγος για την υπογραφή, όπως (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Ο λόγος για την υπογραφή, όπως (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Τύπος του Pdf digital signature.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Τύπος του Pdf digital signature.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Χρονική σήμανση για το Pdf digital signature.
Η προεπιλεγμένη τιμή είναι null.


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Χρονική σήμανση για το Pdf digital signature.
Η προεπιλεγμένη τιμή είναι null.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Επιβολή εμφάνισης/απόκρυψης ιδιοτήτων υπογραφής. Σε περίπτωση που το ShowProperties είναι true η υπογραφή
Το πεδίο έχει προεπιλεγμένη μορφή εμφάνισης.
Ψηφιακά υπογεγραμμένο από {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Ημερομηνία: {Date} Αιτία: {
Reason
(#getReason.getReason/#setReason(String).setReason(String))}
Τοποθεσία: {
Location
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
Το ShowProperties είναι true εξ ορισμού.


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Επιβολή εμφάνισης/απόκρυψης ιδιοτήτων υπογραφής. Σε περίπτωση που το ShowProperties είναι true η υπογραφή
Το πεδίο έχει προεπιλεγμένη μορφή εμφάνισης.
Ψηφιακά υπογεγραμμένο από {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Ημερομηνία: {Date} Αιτία: {
Reason
(#getReason.getReason/#setReason(String).setReason(String))}
Τοποθεσία: {
Location
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
Το ShowProperties είναι true εξ ορισμού.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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


Κλωνοποιήστε την παρουσία Barcode Signature.


**Returns:**
java.lang.Object - Επιστρέφει κλωνοποιημένο αντίτυπο Barcode Signature.

