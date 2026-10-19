---
title: "BarcodeSignature"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Περιέχει ιδιότητες υπογραφής Barcode."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Περιέχει ιδιότητες υπογραφής Barcode.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Αρχικοποιήστε το αντικείμενο BarcodeSignature με το αναγνωριστικό υπογραφής που ελήφθη μετά τη διαδικασία αναζήτησης. |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | Αρχικοποιήστε το BarcodeSignature με προεπιλεγμένες παραμέτρους. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Καθορίζει τον τύπο κωδικοποίησης Barcode. |
|
|  | [getText()](#getText--) | Καθορίζει το κείμενο του Barcode. |
|
|  | [getFormat()](#getFormat--) | Καθορίζει τη μορφή της εικόνας υπογραφής Barcode. |
|
|  | [getContent()](#getContent--) | Καθορίζει το δυαδικό περιεχόμενο εικόνας Barcode τύπου |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
|
|  | [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιήστε την παρουσία Barcode Signature. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Αρχικοποιήστε το αντικείμενο BarcodeSignature με το αναγνωριστικό υπογραφής που ελήφθη μετά τη διαδικασία αναζήτησης.
Αυτό το μοναδικό αναγνωριστικό χρησιμοποιείται για την εύρεση πρόσθετων ιδιοτήτων για αυτήν την υπογραφή από το επίπεδο πληροφοριών υπογραφής του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatureId | java.lang.String | Μοναδικό αναγνωριστικό υπογραφής που λαμβάνεται από τη μέθοδο Sign ή Search της κλάσης Signature [Signature](../../com.groupdocs.signature/signature). |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Αρχικοποιήστε το BarcodeSignature με προεπιλεγμένες παραμέτρους.


### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Καθορίζει τον τύπο κωδικοποίησης Barcode.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Καθορίζει το κείμενο του Barcode.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Καθορίζει τη μορφή της εικόνας υπογραφής Barcode.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Καθορίζει το δυαδικό περιεχόμενο εικόνας Barcode τύπου
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Από προεπιλογή, αυτή η ιδιότητα δεν θα οριστεί.
Χρησιμοποιήστε την ιδιότητα
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) για να ενεργοποιήσετε αυτή τη λειτουργία.


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

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| εικόνα | java.awt.image.BufferedImage |  |

