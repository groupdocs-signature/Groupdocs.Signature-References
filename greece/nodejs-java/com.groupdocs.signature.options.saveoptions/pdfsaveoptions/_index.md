---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Επιλογές αποθήκευσης για έγγραφα PDF."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Επιλογές αποθήκευσης για έγγραφα PDF.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με προεπιλεγμένες τιμές. |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με καθορισμένη μορφή αρχείου εξόδου. |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με σημαία αντικατάστασης. |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με καθορισμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [setFileFormat(int value)](#setFileFormat-int-) | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [toString()](#toString--) | Παρακάμπτει τη μετατροπή σε συμβολοσειρά. |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με προεπιλεγμένες τιμές.

### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με καθορισμένη μορφή αρχείου εξόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileFormat | int | Τύπος αρχείου εξόδου [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με σημαία αντικατάστασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| overwriteExistingFile | boolean | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με καθορισμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileFormat | int | Τύπος αρχείου εξόδου [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
| overwriteExistingFile | boolean | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου.

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Παρακάμπτει τη μετατροπή σε συμβολοσειρά.

**Returns:**
java.lang.String -
