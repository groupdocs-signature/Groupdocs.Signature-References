---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Επιλογές αποθήκευσης για έγγραφα Παρουσίασης."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Επιλογές αποθήκευσης για έγγραφα Παρουσίασης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationSaveOptions()](#PresentationSaveOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με προεπιλεγμένες τιμές. |
| [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με καθορισμένη μορφή αρχείου εξόδου. |
| [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με καθορισμένο τύπο εξόδου και σημαία αντικατάστασης. |
| [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με καθορισμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [setFileFormat(int value)](#setFileFormat-int-) | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [toString()](#toString--) | Παρακάμπτει τη μετατροπή σε συμβολοσειρά. |
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με προεπιλεγμένες τιμές.

### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με καθορισμένη μορφή αρχείου εξόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileFormat | int | Τύπος αρχείου εξόδου [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με καθορισμένο τύπο εξόδου και σημαία αντικατάστασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| overwriteExistingFile | boolean | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με καθορισμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileFormat | int | Τύπος αρχείου εξόδου [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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
