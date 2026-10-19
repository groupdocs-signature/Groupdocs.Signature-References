---
title: "ExportImageSaveOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Επιλογές αποθήκευσης για εξαγωγή εγγράφων σε εικόνα."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Επιλογές αποθήκευσης για εξαγωγή εγγράφων σε εικόνα.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ExportAsImageSaveOptions με προεπιλεγμένες τιμές. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ExportAsImageSaveOptions με καθορισμένη μορφή αρχείου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για εξαγωγή. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για εξαγωγή. |
|
|  | [getExportAllPages()](#getExportAllPages--) | Σημαία για εξαγωγή κάθε σελίδας. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Σημαία για εξαγωγή κάθε σελίδας. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν. |
|
|  | [getPageColumns()](#getPageColumns--) | Λαμβάνει ή ορίζει τον αριθμό των στηλών για τις εξαγόμενες εικόνες. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | Λαμβάνει ή ορίζει τον αριθμό των στηλών για τις εξαγόμενες εικόνες. |
|
|  | [getBorder()](#getBorder--) | Λαμβάνει ή ορίζει τις ρυθμίσεις περιγράμματος εικόνας. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Λαμβάνει ή ορίζει τις ρυθμίσεις περιγράμματος εικόνας. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Τοποθετεί τις σελίδες του εγγράφου σε διαφορετικά πλαίσια σε εικόνα Tiff. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Τοποθετεί τις σελίδες του εγγράφου σε διαφορετικά πλαίσια σε εικόνα Tiff. |
|
|  | [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ExportAsImageSaveOptions με προεπιλεγμένες τιμές.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ExportAsImageSaveOptions με καθορισμένη μορφή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileFormat | int | Μορφή αρχείου εξόδου εικόνας. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για εξαγωγή.
Η ελάχιστη τιμή είναι 1.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του εγγράφου για εξαγωγή.
Η ελάχιστη τιμή είναι 1.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Σημαία για εξαγωγή κάθε σελίδας.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Σημαία για εξαγωγή κάθε σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Επιλογές για τον καθορισμό των σελίδων που θα υπογραφούν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Λαμβάνει ή ορίζει τον αριθμό των στηλών για τις εξαγόμενες εικόνες.
Χρησιμοποιήστε αυτήν την ιδιότητα εάν χρειάζεται να τοποθετήσετε εικόνες σε σειρά.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Λαμβάνει ή ορίζει τον αριθμό των στηλών για τις εξαγόμενες εικόνες.
Χρησιμοποιήστε αυτήν την ιδιότητα εάν χρειάζεται να τοποθετήσετε εικόνες σε σειρά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Αποκτά ή ορίζει τις ρυθμίσεις περιγράμματος εικόνας. Από προεπιλογή αυτή η τιμή δεν έχει οριστεί.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Αποκτά ή ορίζει τις ρυθμίσεις περιγράμματος εικόνας. Από προεπιλογή αυτή η τιμή δεν έχει οριστεί.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Τοποθετεί τις σελίδες του εγγράφου σε διαφορετικά πλαίσια σε εικόνα Tiff.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Τοποθετεί τις σελίδες του εγγράφου σε διαφορετικά πλαίσια σε εικόνα Tiff.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς.


**Returns:**
java.lang.String - 
