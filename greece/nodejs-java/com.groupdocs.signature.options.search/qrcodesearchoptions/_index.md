---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει τις αφηρημένες επιλογές αναζήτησης για υπογραφές QR-Code."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Αντιπροσωπεύει τις αφηρημένες επιλογές αναζήτησης για υπογραφές QR-Code.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης QRCodeSearchOptions με προεπιλεγμένες τιμές. |
| [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης QRCodeSearchOptions με τιμή τύπου κωδικοποίησης. |
| [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης QRCodeSearchOptions με τιμές τύπου κωδικοποίησης και κειμένου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Καθορίζει την ιδιότητα Τύπος Κωδικοποίησης για την αναζήτηση QR-Codes. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Καθορίζει την ιδιότητα Τύπος Κωδικοποίησης για την αναζήτηση QR-Codes. |
| [getText()](#getText--) | Καθορίζει το κείμενο υπογραφής QR-Code εάν πρέπει να αναζητηθεί και να ταιριάξει. |
| [setText(String value)](#setText-java.lang.String-) | Καθορίζει το κείμενο υπογραφής QR-Code εάν πρέπει να αναζητηθεί και να ταιριάξει. |
| [getMatchType()](#getMatchType--) | Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου QR-Code για αναζήτηση. |
| [setMatchType(int value)](#setMatchType-int-) | Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου QR-Code για αναζήτηση. |
| [getDataEncryption()](#getDataEncryption--) | Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Λαμβάνει ή ορίζει την υλοποίηση της διεπαφής [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) για κωδικοποίηση και αποκωδικοποίηση του κειμένου ή των ιδιοτήτων δεδομένων της υπογραφής QR-Code. |
| [getReturnContent()](#getReturnContent--) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας QR-Code της υπογραφής στη σελίδα του εγγράφου. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας QR-Code της υπογραφής στη σελίδα του εγγράφου. |
| [getReturnContentType()](#getReturnContentType--) | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης QRCodeSearchOptions με προεπιλεγμένες τιμές.

### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης QRCodeSearchOptions με τιμή τύπου κωδικοποίησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Καθορίζει τον τύπο κωδικοποίησης QR-Code. |

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης QRCodeSearchOptions με τιμές τύπου κωδικοποίησης και κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Καθορίζει τον τύπο κωδικοποίησης QR-Code. |
| κείμενο | java.lang.String | Ορίστε το κείμενο της υπογραφής QR-Code. |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Καθορίζει την ιδιότητα Τύπος Κωδικοποίησης για την αναζήτηση QR-Codes. Εάν αυτή η τιμή δεν οριστεί, η αναζήτηση εκτελείται για όλους τους υποστηριζόμενους τύπους QR-Code.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Καθορίζει την ιδιότητα Τύπος Κωδικοποίησης για την αναζήτηση QR-Codes. Εάν αυτή η τιμή δεν οριστεί, η αναζήτηση εκτελείται για όλους τους υποστηριζόμενους τύπους QR-Code.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Καθορίζει το κείμενο υπογραφής QR-Code εάν πρέπει να αναζητηθεί και να ταιριάξει.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Καθορίζει το κείμενο υπογραφής QR-Code εάν πρέπει να αναζητηθεί και να ταιριάξει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου QR-Code για αναζήτηση. Χρησιμοποιείται μόνο όταν έχει οριστεί η ιδιότητα Text.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Λαμβάνει ή ορίζει τον τύπο αντιστοίχισης κειμένου QR-Code για αναζήτηση. Χρησιμοποιείται μόνο όταν έχει οριστεί η ιδιότητα Text.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας QR-Code της υπογραφής στη σελίδα του εγγράφου. Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο εικόνας της υπογραφής QR-Code θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με την απαιτούμενη μορφή ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Από προεπιλογή αυτή η επιλογή είναι απενεργοποιημένη.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας QR-Code της υπογραφής στη σελίδα του εγγράφου. Εάν αυτή η σημαία οριστεί σε true, το περιεχόμενο εικόνας της υπογραφής QR-Code θα διατηρήσει τα ακατέργαστα δεδομένα εικόνας με την απαιτούμενη μορφή ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Από προεπιλογή αυτή η επιλογή είναι απενεργοποιημένη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει ότι η εικόνα QR-Code θα επιστραφεί στην αρχική μορφή. Αυτή η μορφή εικόνας καθορίζεται στο QrCodeSignature.Format (). Οι πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP. Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε θα επιστραφεί η εικόνα QR-Code σε αρχική μορφή .png.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Καθορίζει τον τύπο αρχείου του επιστρεφόμενου περιεχομένου εικόνας της υπογραφής QR-Code όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. Από προεπιλογή ορίζεται σε Null. Αυτό σημαίνει ότι η εικόνα QR-Code θα επιστραφεί στην αρχική μορφή. Αυτή η μορφή εικόνας καθορίζεται στο QrCodeSignature.Format (). Οι πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP. Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε θα επιστραφεί η εικόνα QR-Code σε αρχική μορφή .png.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

