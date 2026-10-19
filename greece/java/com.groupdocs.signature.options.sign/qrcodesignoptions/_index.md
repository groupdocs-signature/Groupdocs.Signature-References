---
title: "QrCodeSignOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αντιπροσωπεύει τις επιλογές υπογραφής QR-Code."
type: docs
weight: 15
url: /el/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Αντιπροσωπεύει τις επιλογές υπογραφής QR-Code.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSignOptions με προεπιλεγμένες τιμές. |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSignOptions με κείμενο. |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeSignOptions με κείμενο. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Λαμβάνει ή ορίζει τον τύπο QRCode. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Λαμβάνει ή ορίζει τον τύπο QRCode. |
|
|  | [getForeColor()](#getForeColor--) | Λαμβάνει ή ορίζει το χρώμα Fore των ράβδων QR-Code |
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Λαμβάνει ή ορίζει το χρώμα Fore των ράβδων QR-Code |
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Λαμβάνει ή ορίζει το χρώμα Fore των ράβδων QR-Code |
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση.
|
|  | [getInnerMargins()](#getInnerMargins--) | Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων QRCode και των περιγραμμάτων της τελικής εικόνας. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων QRCode και των περιγραμμάτων της τελικής εικόνας. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Λαμβάνει ή ορίζει την ευθυγράμμιση του κειμένου στην τελική εικόνα QR-code. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Λαμβάνει ή ορίζει την ευθυγράμμιση του κειμένου στην τελική εικόνα QR-code. |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | Λαμβάνει ή ορίζει το όνομα αρχείου εικόνας λογότυπου QR-code. |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα αρχείου εικόνας λογότυπου QR-code. |
|
|  | [getLogoStream()](#getLogoStream--) | Λαμβάνει ή ορίζει τη ροή εικόνας λογότυπου QR-code. |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Λαμβάνει ή ορίζει τη ροή εικόνας λογότυπου QR-code. |
|
|  | [getData()](#getData--) | Λαμβάνει ή ορίζει προσαρμοσμένο αντικείμενο για σειριοποίηση στο περιεχόμενο QR-Code. |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | Λαμβάνει ή ορίζει προσαρμοσμένο αντικείμενο για σειριοποίηση στο περιεχόμενο QR-Code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code. |
|
|  | [getReturnContent()](#getReturnContent--) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας QR-Code μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας QR-Code μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
|
|  | [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς. |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSignOptions με προεπιλεγμένες τιμές.


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης QRCodeSignOptions με κείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Κείμενο υπογραφής. |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeSignOptions με κείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Κείμενο QRCode |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Τύπος κωδικοποίησης QRCode, δείτε [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Λαμβάνει ή ορίζει τον τύπο QRCode.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Λαμβάνει ή ορίζει τον τύπο QRCode.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Λαμβάνει ή ορίζει το χρώμα Fore των ράβδων QR-Code
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα Fore των ράβδων QR-Code
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Λαμβάνει ή ορίζει το χρώμα Fore των ράβδων QR-Code
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων QRCode και των περιγραμμάτων της τελικής εικόνας.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Λαμβάνει ή ορίζει το διάστημα μεταξύ των στοιχείων QRCode και των περιγραμμάτων της τελικής εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Λαμβάνει ή ορίζει την ευθυγράμμιση του κειμένου στην τελική εικόνα QR-code.
Η προεπιλεγμένη τιμή είναι None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Λαμβάνει ή ορίζει την ευθυγράμμιση του κειμένου στην τελική εικόνα QR-code.
Η προεπιλεγμένη τιμή είναι None.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Λαμβάνει ή ορίζει το όνομα αρχείου εικόνας λογότυπου QR-code.
Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το LogoStream.
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Λαμβάνει ή ορίζει το όνομα αρχείου εικόνας λογότυπου QR-code.
Αυτή η ιδιότητα χρησιμοποιείται μόνο εάν δεν έχει καθοριστεί το LogoStream.
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Λαμβάνει ή ορίζει τη ροή εικόνας λογότυπου QR-code.
Εάν αυτή η ιδιότητα καθοριστεί, χρησιμοποιείται πάντα αντί του LogoGuid.
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Λαμβάνει ή ορίζει τη ροή εικόνας λογότυπου QR-code.
Εάν αυτή η ιδιότητα καθοριστεί, χρησιμοποιείται πάντα αντί του LogoGuid.
Η χρήση αυτής της ιδιότητας μπορεί να προκαλέσει προβλήματα με την επαλήθευση. Χρησιμοποιήστε την προσεκτικά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Λαμβάνει ή ορίζει προσαρμοσμένο αντικείμενο για σειριοποίηση στο περιεχόμενο QR-Code.


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Λαμβάνει ή ορίζει προσαρμοσμένο αντικείμενο για σειριοποίηση στο περιεχόμενο QR-Code.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας QR-Code μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου.
Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο εικόνας της υπογραφής QR-Code θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με την απαιτούμενη μορφή.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Από προεπιλογή, αυτή η επιλογή είναι απενεργοποιημένη.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας QR-Code μιας υπογραφής που τοποθετήθηκε στη σελίδα του εγγράφου.
Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο εικόνας της υπογραφής QR-Code θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με την απαιτούμενη μορφή.
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


Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη.
Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει ότι θα επιστραφεί το περιεχόμενο εικόνας QR-Code στην αρχική μορφή.
Αυτή η μορφή εικόνας καθορίζεται στο
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP.
Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο εικόνας QR-Code σε μορφή .png θα επιστραφεί.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη.
Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει ότι θα επιστραφεί το περιεχόμενο εικόνας QR-Code στην αρχική μορφή.
Αυτή η μορφή εικόνας καθορίζεται στο
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP.
Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο εικόνας QR-Code σε μορφή .png θα επιστραφεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς.


**Returns:**
java.lang.String - 
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
