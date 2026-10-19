---
title: "BarcodeSignOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει τις επιλογές υπογραφής Barcode."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Αντιπροσωπεύει τις επιλογές υπογραφής Barcode.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeSignOptions με προεπιλεγμένες τιμές. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeSignOptions με κείμενο. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeSignOptions με κείμενο. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Λαμβάνει ή ορίζει τον τύπο Barcode. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Λαμβάνει ή ορίζει τον τύπο Barcode. |
|
|  | [getForeColor()](#getForeColor--) | Λαμβάνει ή ορίζει το χρώμα Fore των γραμμών Barcode |
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Λαμβάνει ή ορίζει το χρώμα Fore των γραμμών Barcode |
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Λαμβάνει ή ορίζει το χρώμα Fore των γραμμών Barcode |
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση.
|
|  | [getInnerMargins()](#getInnerMargins--) | Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων Barcode και των ορίων της τελικής εικόνας. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων Barcode και των ορίων της τελικής εικόνας. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Λαμβάνει ή ορίζει τη στοίχιση του κειμένου στην τελική εικόνα Barcode. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Λαμβάνει ή ορίζει τη στοίχιση του κειμένου στην τελική εικόνα Barcode. |
|
|  | [getReturnContent()](#getReturnContent--) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας Barcode μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας Barcode μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Καθορίζει τον τύπο αρχείου του περιεχομένου εικόνας που επιστρέφεται από την υπογραφή Barcode όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Καθορίζει τον τύπο αρχείου του περιεχομένου εικόνας που επιστρέφεται από την υπογραφή Barcode όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
|
|  | [validate()](#validate--) | Εσωτερική μέθοδος για την επικύρωση των παραμέτρων επιλογών Barcode. |
|
|  | [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeSignOptions με προεπιλεγμένες τιμές.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeSignOptions με κείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Κείμενο Barcode |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeSignOptions με κείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Κείμενο Barcode |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Τύπος κωδικοποίησης Barcode, δείτε [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Λαμβάνει ή ορίζει τον τύπο Barcode.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Λαμβάνει ή ορίζει τον τύπο Barcode.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Λαμβάνει ή ορίζει το χρώμα Fore των γραμμών Barcode
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα Fore των γραμμών Barcode
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Λαμβάνει ή ορίζει το χρώμα Fore των γραμμών Barcode
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων Barcode και των ορίων της τελικής εικόνας.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων Barcode και των ορίων της τελικής εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Λαμβάνει ή ορίζει τη στοίχιση του κειμένου στην τελική εικόνα Barcode.
Η προεπιλεγμένη τιμή είναι None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Λαμβάνει ή ορίζει τη στοίχιση του κειμένου στην τελική εικόνα Barcode.
Η προεπιλεγμένη τιμή είναι None.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας Barcode μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου.
Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο εικόνας της υπογραφής Barcode θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με τη ζητούμενη μορφή.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Από προεπιλογή, αυτή η επιλογή είναι απενεργοποιημένη.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας Barcode μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου.
Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο εικόνας της υπογραφής Barcode θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με τη ζητούμενη μορφή.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Από προεπιλογή, αυτή η επιλογή είναι απενεργοποιημένη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Καθορίζει τον τύπο αρχείου του περιεχομένου εικόνας που επιστρέφεται από την υπογραφή Barcode όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη.
Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει ότι θα επιστραφεί το περιεχόμενο εικόνας Barcode στην αρχική μορφή.
Αυτή η μορφή εικόνας καθορίζεται στο
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP.
Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο εικόνας Barcode θα επιστραφεί σε μορφή .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Καθορίζει τον τύπο αρχείου του περιεχομένου εικόνας που επιστρέφεται από την υπογραφή Barcode όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη.
Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει ότι θα επιστραφεί το περιεχόμενο εικόνας Barcode στην αρχική μορφή.
Αυτή η μορφή εικόνας καθορίζεται στο
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
Πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP.
Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο εικόνας Barcode θα επιστραφεί σε μορφή .png.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Εσωτερική μέθοδος για την επικύρωση των παραμέτρων επιλογών Barcode.


### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς.


**Returns:**
java.lang.String - 
