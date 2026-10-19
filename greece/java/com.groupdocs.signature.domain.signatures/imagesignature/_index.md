---
title: "ImageSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες υπογραφής εικόνας."
type: docs
weight: 14
url: /el/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Περιέχει ιδιότητες υπογραφής εικόνας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Αρχικοποιήστε το αντικείμενο ImageSignature με το αναγνωριστικό υπογραφής που ελήφθη μετά τη διαδικασία αναζήτησης. |
|
|  | [ImageSignature()](#ImageSignature--) | Αρχικοποιήστε το ImageSignature με προεπιλεγμένες παραμέτρους. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSize()](#getSize--) | Καθορίζει το μέγεθος σε byte της εικόνας υπογραφής. |
|
|  | [setSize(int value)](#setSize-int-) | Καθορίζει το μέγεθος σε byte της εικόνας υπογραφής. |
|
|  | [getFormat()](#getFormat--) | Καθορίζει τη μορφή της εικόνας υπογραφής. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Καθορίζει τη μορφή της εικόνας υπογραφής. |
|
|  | [getContent()](#getContent--) | Καθορίζει το περιεχόμενο των δυαδικών δεδομένων της εικόνας τύπου |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιήστε την παρουσία Barcode Signature. |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Αρχικοποιήστε το αντικείμενο ImageSignature με το αναγνωριστικό υπογραφής που ελήφθη μετά τη διαδικασία αναζήτησης.
Αυτό το μοναδικό αναγνωριστικό χρησιμοποιείται για την εύρεση πρόσθετων ιδιοτήτων για αυτήν την υπογραφή από το επίπεδο πληροφοριών υπογραφής του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatureId | java.lang.String | Μοναδικό αναγνωριστικό υπογραφής που λαμβάνεται από τη μέθοδο Sign ή Search της κλάσης Signature [Signature](../../com.groupdocs.signature/signature). |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Αρχικοποιήστε το ImageSignature με προεπιλεγμένες παραμέτρους.


### getSize() {#getSize--}
```
public final int getSize()
```


Καθορίζει το μέγεθος σε byte της εικόνας υπογραφής.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Καθορίζει το μέγεθος σε byte της εικόνας υπογραφής.



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Καθορίζει τη μορφή της εικόνας υπογραφής.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Καθορίζει τη μορφή της εικόνας υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Καθορίζει το περιεχόμενο των δυαδικών δεδομένων της εικόνας τύπου
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Από προεπιλογή, αυτή η ιδιότητα δεν θα οριστεί.
Χρησιμοποιήστε την ιδιότητα
ImageSearchOptions.ReturnContent
({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) για την ενεργοποίηση αυτής της λειτουργίας.


**Returns:**
byte[]
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

