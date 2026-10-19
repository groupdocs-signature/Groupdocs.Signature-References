---
title: "PdfSaveOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Επιλογές αποθήκευσης για έγγραφα PDF."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
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
|  | [PdfSaveOptions()](#PdfSaveOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με προεπιλεγμένες τιμές. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με συγκεκριμένη μορφή αρχείου εξόδου. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με σημαία αντικατάστασης. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με συγκεκριμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Αποκτά ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Αποκτά ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Ένας κωδικός πρόσβασης δικαιωμάτων (ο κύριος κωδικός) απαιτεί κωδικό πρόσβασης για την αλλαγή των ρυθμίσεων δικαιωμάτων. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Ένας κωδικός πρόσβασης δικαιωμάτων (ο κύριος κωδικός) απαιτεί κωδικό πρόσβασης για την αλλαγή των ρυθμίσεων δικαιωμάτων. |
|
|  | [getPermissions()](#getPermissions--) | Τα δικαιώματα του εγγράφου PDF όπως η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Τα δικαιώματα του εγγράφου PDF όπως η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων. |
|
|  | [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με προεπιλεγμένες τιμές.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με συγκεκριμένη μορφή αρχείου εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileFormat | int | Τύπος αρχείου εξόδου [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με σημαία αντικατάστασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PdfSaveOptions με συγκεκριμένη μορφή αρχείου εξόδου και σημαία αντικατάστασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileFormat | int | Τύπος αρχείου εξόδου [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
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

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Ένας κωδικός πρόσβασης δικαιωμάτων (ο κύριος κωδικός) απαιτεί κωδικό πρόσβασης για την αλλαγή των ρυθμίσεων δικαιωμάτων.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Ένας κωδικός πρόσβασης δικαιωμάτων (ο κύριος κωδικός) απαιτεί κωδικό πρόσβασης για την αλλαγή των ρυθμίσεων δικαιωμάτων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Τα δικαιώματα του εγγράφου PDF όπως η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων.


Για να τροποποιήσετε αυτά τα δικαιώματα, το
PermissionsPassword
πρέπει να οριστεί.
Η τιμή είναι ένας συνδυασμός σημαιών από [Permissions](../../com.groupdocs.signature.options/permissions).
Ένα
null
η τιμή σημαίνει ότι δεν εφαρμόζονται ρητά δικαιώματα.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Τα δικαιώματα του εγγράφου PDF όπως η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς.


**Returns:**
java.lang.String - 
