---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Επιλογές αποθήκευσης για έγγραφα Επεξεργασίας Κειμένου."
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Επιλογές αποθήκευσης για έγγραφα Επεξεργασίας Κειμένου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με προεπιλεγμένες τιμές. |
| [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με καθορισμένη μορφή αρχείου εξόδου. |
| [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με καθορισμένο τύπο εξόδου και σημαία αντικατάστασης. |
| [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με καθορισμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [setFileFormat(int value)](#setFileFormat-int-) | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς |
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με προεπιλεγμένες τιμές.

### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με καθορισμένη μορφή αρχείου εξόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileFormat | int | Τύπος αρχείου εξόδου [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με καθορισμένο τύπο εξόδου και σημαία αντικατάστασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| overwriteExistingFile | boolean | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης WordProcessingSaveOptions με καθορισμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileFormat | int | Τύπος αρχείου εξόδου [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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


Παράκαμψη μετατροπής συμβολοσειράς

**Returns:**
java.lang.String -
