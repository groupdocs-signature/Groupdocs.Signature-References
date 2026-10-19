---
title: "ImageSearchOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αναπαριστά επιλογές αναζήτησης για υπογραφές εικόνας."
type: docs
weight: 14
url: /el/java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Αναπαριστά επιλογές αναζήτησης για υπογραφές εικόνας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ImageSearchOptions()](#ImageSearchOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης ImageSearchOptions με προεπιλεγμένες τιμές. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getReturnContent()](#getReturnContent--) | Λαμβάνει ή ορίζει τη σημαία για τη λήψη του περιεχομένου εικόνας της υπογραφής στη σελίδα του εγγράφου. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Λαμβάνει ή ορίζει τη σημαία για τη λήψη του περιεχομένου εικόνας της υπογραφής στη σελίδα του εγγράφου. |
|
|  | [getMinContentSize()](#getMinContentSize--) | Για μη μηδενική τιμή, αυτή η σημαία καθορίζει το ελάχιστο μέγεθος των εικόνων για τα κριτήρια αναζήτησης. |
|
|  | [setMinContentSize(long value)](#setMinContentSize-long-) | Για μη μηδενική τιμή, αυτή η σημαία καθορίζει το ελάχιστο μέγεθος των εικόνων για τα κριτήρια αναζήτησης. |
|
|  | [getMaxContentSize()](#getMaxContentSize--) | Για μη μηδενική τιμή, αυτή η σημαία καθορίζει το μέγιστο μέγεθος των εικόνων για τα κριτήρια αναζήτησης. |
|
|  | [setMaxContentSize(long value)](#setMaxContentSize-long-) | Για μη μηδενική τιμή, αυτή η σημαία καθορίζει το μέγιστο μέγεθος των εικόνων για τα κριτήρια αναζήτησης. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου της εικόνας υπογραφής όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου της εικόνας υπογραφής όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
|
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης ImageSearchOptions με προεπιλεγμένες τιμές.


### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Λαμβάνει ή ορίζει τη σημαία για τη λήψη του περιεχομένου εικόνας της υπογραφής στη σελίδα του εγγράφου.
Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο της εικόνας υπογραφής θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με την απαιτούμενη μορφή.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Από προεπιλογή, αυτή η επιλογή είναι απενεργοποιημένη.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για τη λήψη του περιεχομένου εικόνας της υπογραφής στη σελίδα του εγγράφου.
Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο της εικόνας υπογραφής θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με την απαιτούμενη μορφή.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Από προεπιλογή, αυτή η επιλογή είναι απενεργοποιημένη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


Για μη μηδενική τιμή, αυτή η σημαία καθορίζει το ελάχιστο μέγεθος των εικόνων για τα κριτήρια αναζήτησης.
Από προεπιλογή, αυτή η σημαία ορίζεται σε μηδέν και δεν επηρεάζει το αποτέλεσμα της αναζήτησης.


**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


Για μη μηδενική τιμή, αυτή η σημαία καθορίζει το ελάχιστο μέγεθος των εικόνων για τα κριτήρια αναζήτησης.
Από προεπιλογή, αυτή η σημαία ορίζεται σε μηδέν και δεν επηρεάζει το αποτέλεσμα της αναζήτησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


Για μη μηδενική τιμή, αυτή η σημαία καθορίζει το μέγιστο μέγεθος των εικόνων για τα κριτήρια αναζήτησης.
Από προεπιλογή, αυτή η σημαία ορίζεται σε μηδέν και δεν επηρεάζει το αποτέλεσμα της αναζήτησης.


**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


Για μη μηδενική τιμή, αυτή η σημαία καθορίζει το μέγιστο μέγεθος των εικόνων για τα κριτήρια αναζήτησης.
Από προεπιλογή, αυτή η σημαία ορίζεται σε μηδέν και δεν επηρεάζει το αποτέλεσμα της αναζήτησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου της εικόνας υπογραφής όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη.
Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει ότι θα επιστραφεί το περιεχόμενο της εικόνας στην αρχική μορφή.
Αυτή η μορφή εικόνας καθορίζεται στο
ImageSignature.Format

Πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP.
Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο της εικόνας στην αρχική μορφή θα επιστραφεί.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου της εικόνας υπογραφής όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη.
Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει ότι θα επιστραφεί το περιεχόμενο της εικόνας στην αρχική μορφή.
Αυτή η μορφή εικόνας καθορίζεται στο
ImageSignature.Format

Πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP.
Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο της εικόνας στην αρχική μορφή θα επιστραφεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

