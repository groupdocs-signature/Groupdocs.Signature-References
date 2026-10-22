---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αναπαριστά τις επιλογές Barcode signature."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Αναπαριστά τις επιλογές Barcode signature.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BarcodeSignOptions()](#BarcodeSignOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης **BarcodeSignOptions** με προεπιλεγμένες τιμές. |
| [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης **BarcodeSignOptions** με κείμενο. |
| [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Αρχικοποιεί μια νέα παρουσία της κλάσης **BarcodeSignOptions** με κείμενο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Λαμβάνει ή ορίζει τον τύπο του **Barcode**. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Λαμβάνει ή ορίζει τον τύπο του **Barcode**. |
| [getForeColor()](#getForeColor--) | Λαμβάνει ή ορίζει το χρώμα **Fore** των ράβδων του **Barcode**. Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Λαμβάνει ή ορίζει το χρώμα **Fore** των ράβδων του **Barcode**. Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. |
| [setForeColor(String value)](#setForeColor-java.lang.String-) | Λαμβάνει ή ορίζει το χρώμα **Fore** των ράβδων του **Barcode**. Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. |
| [getInnerMargins()](#getInnerMargins--) | Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων του **Barcode** και των ορίων της τελικής εικόνας. |
| [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων του **Barcode** και των ορίων της τελικής εικόνας. |
| [getCodeTextAlignment()](#getCodeTextAlignment--) | Λαμβάνει ή ορίζει την ευθυγράμμιση του κειμένου στην τελική εικόνα του **Barcode**. |
| [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Λαμβάνει ή ορίζει την ευθυγράμμιση του κειμένου στην τελική εικόνα του **Barcode**. |
| [getReturnContent()](#getReturnContent--) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας **Barcode** μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας **Barcode** μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου. |
| [getReturnContentType()](#getReturnContentType--) | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής **Barcode** όταν η ιδιότητα **ReturnContent** είναι ενεργοποιημένη. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής **Barcode** όταν η ιδιότητα **ReturnContent** είναι ενεργοποιημένη. |
| [validate()](#validate--) | Εσωτερική μέθοδος για την επικύρωση των παραμέτρων επιλογών του **Barcode**. |
| [toString()](#toString--) | Παρακάμπτει τη μετατροπή σε συμβολοσειρά. |
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης **BarcodeSignOptions** με προεπιλεγμένες τιμές.

### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης **BarcodeSignOptions** με κείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Κείμενο **Barcode** |

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης **BarcodeSignOptions** με κείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Κείμενο **Barcode** |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Τύπος κωδικοποίησης Barcode, δείτε [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Λαμβάνει ή ορίζει τον τύπο του **Barcode**.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Λαμβάνει ή ορίζει τον τύπο του **Barcode**.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Λαμβάνει ή ορίζει το χρώμα **Fore** των ράβδων του **Barcode**. Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε το προσεκτικά.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα **Fore** των ράβδων του **Barcode**. Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε το προσεκτικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Λαμβάνει ή ορίζει το χρώμα **Fore** των ράβδων του **Barcode**. Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε το προσεκτικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων του **Barcode** και των ορίων της τελικής εικόνας.

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων του **Barcode** και των ορίων της τελικής εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Λαμβάνει ή ορίζει την ευθυγράμμιση του κειμένου στην τελική εικόνα του **Barcode**. Η προεπιλεγμένη τιμή είναι **None**.

**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Λαμβάνει ή ορίζει την ευθυγράμμιση του κειμένου στην τελική εικόνα του **Barcode**. Η προεπιλεγμένη τιμή είναι **None**.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας **Barcode** μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου. Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο εικόνας της υπογραφής **Barcode** θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με την απαιτούμενη μορφή **ReturnContentType** (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Από προεπιλογή αυτή η επιλογή είναι απενεργοποιημένη.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας **Barcode** μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου. Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο εικόνας της υπογραφής **Barcode** θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με την απαιτούμενη μορφή **ReturnContentType** (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Από προεπιλογή αυτή η επιλογή είναι απενεργοποιημένη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής **Barcode** όταν η ιδιότητα **ReturnContent** είναι ενεργοποιημένη. Από προεπιλογή ορίζεται σε **Null**. Αυτό σημαίνει ότι θα επιστραφεί το περιεχόμενο εικόνας **Barcode** στην αρχική μορφή. Αυτή η μορφή εικόνας καθορίζεται στο **BarcodeSignature.Format** ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}). Οι πιθανές υποστηριζόμενες τιμές είναι: **FileType.JPEG**, **FileType.PNG**, **FileType.BMP**. Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο εικόνας **Barcode** θα επιστραφεί σε μορφή .png.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής **Barcode** όταν η ιδιότητα **ReturnContent** είναι ενεργοποιημένη. Από προεπιλογή ορίζεται σε **Null**. Αυτό σημαίνει ότι θα επιστραφεί το περιεχόμενο εικόνας **Barcode** στην αρχική μορφή. Αυτή η μορφή εικόνας καθορίζεται στο **BarcodeSignature.Format** ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)) Οι πιθανές υποστηριζόμενες τιμές είναι: **FileType.JPEG**, **FileType.PNG**, **FileType.BMP**. Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο εικόνας **Barcode** θα επιστραφεί σε μορφή .png.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Εσωτερική μέθοδος για την επικύρωση των παραμέτρων επιλογών του **Barcode**.

### toString() {#toString--}
```
public String toString()
```


Παρακάμπτει τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
