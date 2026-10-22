---
title: "QrCodeSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει ιδιότητες QR-code signature."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Περιέχει ιδιότητες QR-code signature.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Αρχικοποιήστε το αντικείμενο QrCodeSignature με το αναγνωριστικό υπογραφής που ελήφθη μετά τη διαδικασία αναζήτησης. |
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Καθορίζει τον τύπο κωδικοποίησης QR-code. |
| [getText()](#getText--) | Καθορίζει το κείμενο του QR-code. |
| [getFormat()](#getFormat--) | Καθορίζει τη μορφή της εικόνας υπογραφής QR-code. |
| [getContent()](#getContent--) | Καθορίζει το περιεχόμενο εικόνας δυαδικών δεδομένων QR-code τύπου Format (\\#getFormat.getFormat/\\#setFormat(FileType).setFormat(FileType)). |
| [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Αποκτήστε το αντικείμενο από το κείμενο υπογραφής QR-Code μέσω απο-σειροποίησης. |
| [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Αποκτήστε το αντικείμενο από το κείμενο υπογραφής QR-Code μέσω απο-σειροποίησης. |
| [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
| [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
| [deepClone()](#deepClone--) | Κλωνοποιήστε το αντίτυπο υπογραφής QR-Code. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Αρχικοποιήστε το αντικείμενο QrCodeSignature με το αναγνωριστικό υπογραφής που ελήφθη μετά τη διαδικασία αναζήτησης. Αυτό το μοναδικό αναγνωριστικό χρησιμοποιείται για την εύρεση πρόσθετων ιδιοτήτων για αυτήν την υπογραφή από το επίπεδο πληροφοριών υπογραφής του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signatureId | java.lang.String | Μοναδικό αναγνωριστικό υπογραφής που λαμβάνεται με τη μέθοδο υπογραφής ή αναζήτησης. |

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Καθορίζει τον τύπο κωδικοποίησης QR-code.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Καθορίζει το κείμενο του QR-code.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Καθορίζει τη μορφή της εικόνας υπογραφής QR-code.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Καθορίζει το περιεχόμενο εικόνας δυαδικών δεδομένων QR-code τύπου Format (\\#getFormat.getFormat/\\#setFormat(FileType).setFormat(FileType)). Από προεπιλογή αυτή η ιδιότητα δεν θα οριστεί. Χρησιμοποιήστε την ιδιότητα QrCodeSearchOptions.ReturnContent ([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions\\#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions\\#setReturnContent-boolean-)) για να ενεργοποιήσετε αυτή τη δυνατότητα.

**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Αποκτήστε το αντικείμενο από το κείμενο υπογραφής QR-Code μέσω απο-σειροποίησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | java.lang.Class<T> |  |

**Returns:**
T -  T : Τύπος αντικειμένου για απο-σειροποίηση από το κείμενο QR-Code
### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Αποκτήστε το αντικείμενο από το κείμενο υπογραφής QR-Code μέσω απο-σειροποίησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Ορίστε προσαρμοσμένη υλοποίηση κρυπτογράφησης δεδομένων |

T : Τύπος αντικειμένου για απο-σειροποίηση από το κείμενο QR-Code |
| τύπος | java.lang.Class<T> |  |

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


Κλωνοποιήστε το αντίτυπο υπογραφής QR-Code.

**Returns:**
java.lang.Object - Επιστρέφει κλωνοποιημένο αντίτυπο υπογραφής QR-code.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| εικόνα | java.awt.image.BufferedImage |  |

