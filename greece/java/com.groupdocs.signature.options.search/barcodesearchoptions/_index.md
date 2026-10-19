---
title: "BarcodeSearchOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Αναπαριστά τις αφηρημένες επιλογές αναζήτησης για υπογραφές Barcode."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Αναπαριστά τις αφηρημένες επιλογές αναζήτησης για υπογραφές Barcode.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SearchBarcodeOptions με προεπιλεγμένες τιμές. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SearchBarcodeOptions με τιμή τύπου κωδικοποίησης. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SearchBarcodeOptions με τύπο κωδικοποίησης και τιμές κειμένου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Καθορίζει την ιδιότητα Encode Type για την αναζήτηση κωδικών Barcode. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Καθορίζει την ιδιότητα Encode Type για την αναζήτηση κωδικών Barcode. |
|
|  | [getText()](#getText--) | Καθορίζει το κείμενο της υπογραφής Barcode εάν πρέπει να αναζητηθεί και να ταιριάξει. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Καθορίζει το κείμενο της υπογραφής Barcode εάν πρέπει να αναζητηθεί και να ταιριάξει. |
|
|  | [getMatchType()](#getMatchType--) | Λαμβάνει ή ορίζει την αναζήτηση τύπου αντιστοίχισης κειμένου Barcode. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Λαμβάνει ή ορίζει την αναζήτηση τύπου αντιστοίχισης κειμένου Barcode. |
|
|  | [getReturnContent()](#getReturnContent--) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας Barcode της υπογραφής στη σελίδα του εγγράφου. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας Barcode της υπογραφής στη σελίδα του εγγράφου. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Καθορίζει τον τύπο αρχείου του περιεχομένου εικόνας που επιστρέφεται από την υπογραφή Barcode όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Καθορίζει τον τύπο αρχείου του περιεχομένου εικόνας που επιστρέφεται από την υπογραφή Barcode όταν η ιδιότητα ReturnContent είναι ενεργοποιημένη. |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SearchBarcodeOptions με προεπιλεγμένες τιμές.


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SearchBarcodeOptions με τιμή τύπου κωδικοποίησης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Καθορίζει τον τύπο κωδικοποίησης Barcode. |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SearchBarcodeOptions με τύπο κωδικοποίησης και τιμές κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Καθορίζει τον τύπο κωδικοποίησης Barcode. |
|
|  | κείμενο | java.lang.String | Ορίστε το κείμενο της υπογραφής Barcode. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Καθορίζει την ιδιότητα Encode Type για την αναζήτηση κωδικών Barcode.
Εάν αυτή η τιμή δεν έχει οριστεί, η αναζήτηση επεξεργάζεται για όλους τους υποστηριζόμενους τύπους Barcode.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Καθορίζει την ιδιότητα Encode Type για την αναζήτηση κωδικών Barcode.
Εάν αυτή η τιμή δεν έχει οριστεί, η αναζήτηση επεξεργάζεται για όλους τους υποστηριζόμενους τύπους Barcode.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Καθορίζει το κείμενο της υπογραφής Barcode εάν πρέπει να αναζητηθεί και να ταιριάξει.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Καθορίζει το κείμενο της υπογραφής Barcode εάν πρέπει να αναζητηθεί και να ταιριάξει.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Λαμβάνει ή ορίζει την αναζήτηση τύπου αντιστοίχισης κειμένου Barcode. Χρησιμοποιείται μόνο όταν η ιδιότητα Text έχει οριστεί.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Λαμβάνει ή ορίζει την αναζήτηση τύπου αντιστοίχισης κειμένου Barcode. Χρησιμοποιείται μόνο όταν η ιδιότητα Text έχει οριστεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας Barcode της υπογραφής στη σελίδα του εγγράφου.
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


Λαμβάνει ή ορίζει τη σημαία για λήψη του περιεχομένου εικόνας Barcode της υπογραφής στη σελίδα του εγγράφου.
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
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Πιθανές υποστηριζόμενες τιμές είναι: FileType.JPEG, FileType.PNG, FileType.BMP.
Εάν η παρεχόμενη μορφή δεν υποστηρίζεται, τότε το περιεχόμενο εικόνας Barcode θα επιστραφεί σε μορφή .png.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

