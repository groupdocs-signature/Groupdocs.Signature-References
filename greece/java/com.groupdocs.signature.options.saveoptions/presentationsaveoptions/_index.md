---
title: "PresentationSaveOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Επιλογές αποθήκευσης για έγγραφα Παρουσίασης."
type: docs
weight: 12
url: /el/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
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
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με προεπιλεγμένες τιμές. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με συγκεκριμένη μορφή αρχείου εξόδου. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με συγκεκριμένο τύπο εξόδου και σημαία αντικατάστασης. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Αρχικοποιεί ένα νέο αντίγραφο της κλάσης PresentationSaveOptions με καθορισμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Αποκτά ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Αποκτά ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
|
|  | [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με προεπιλεγμένες τιμές.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με συγκεκριμένη μορφή αρχείου εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileFormat | int | Τύπος αρχείου εξόδου [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationSaveOptions με συγκεκριμένο τύπο εξόδου και σημαία αντικατάστασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντίγραφο της κλάσης PresentationSaveOptions με καθορισμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileFormat | int | Τύπος αρχείου εξόδου [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|
|  | overwriteExistingFile | boolean | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Αποκτά ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Αποκτά ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς.


**Returns:**
java.lang.String - 
