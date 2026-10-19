---
title: "SaveOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Επιτρέπει τον καθορισμό πρόσθετων επιλογών, όπως κωδικός πρόσβασης, κατά την αποθήκευση ενός εγγράφου για υπογραφή."
type: docs
weight: 13
url: /el/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως κωδικός πρόσβασης) κατά την αποθήκευση ενός εγγράφου για υπογραφή.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SaveOptions με προεπιλεγμένες τιμές. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SaveOptions με καθορισμένο τύπο εξόδου και σημαία αντικατάστασης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Λαμβάνει ή ορίζει αν θα αντικατασταθεί το υπάρχον αρχείο με το νέο αρχείο εξόδου. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Λαμβάνει ή ορίζει αν θα αντικατασταθεί το υπάρχον αρχείο με το νέο αρχείο εξόδου. |
|
|  | [getPassword()](#getPassword--) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για την αποθήκευση του υπογεγραμμένου εγγράφου με προστασία κωδικού. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για την αποθήκευση του υπογεγραμμένου εγγράφου με προστασία κωδικού. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | Λαμβάνει ή ορίζει αν θα χρησιμοποιηθεί ο κωδικός πρόσβασης από το LoadOptions για την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Λαμβάνει ή ορίζει αν θα χρησιμοποιηθεί ο κωδικός πρόσβασης από το LoadOptions για την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Λαμβάνει ή ορίζει τη σημαία για αυτόματη προσθήκη επέκτασης όταν λείπει στη διαδρομή του αρχείου εξόδου. |
Η προεπιλεγμένη τιμή είναι ψευδής.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Λαμβάνει ή ορίζει τη σημαία για αυτόματη προσθήκη επέκτασης όταν λείπει στη διαδρομή του αρχείου εξόδου. |
Η προεπιλεγμένη τιμή είναι ψευδής.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SaveOptions με προεπιλεγμένες τιμές.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SaveOptions με καθορισμένο τύπο εξόδου και σημαία αντικατάστασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Σημαία που καθορίζει αν θα αντικατασταθεί το υπογεγραμμένο αρχείο με το ίδιο αρχείο. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Λαμβάνει ή ορίζει αν θα αντικατασταθεί το υπάρχον αρχείο με το νέο αρχείο εξόδου.
Διαφορετικά, θα δημιουργηθεί νέο αρχείο με αριθμό ως επίθημα.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Λαμβάνει ή ορίζει αν θα αντικατασταθεί το υπάρχον αρχείο με το νέο αρχείο εξόδου.
Διαφορετικά, θα δημιουργηθεί νέο αρχείο με αριθμό ως επίθημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για την αποθήκευση του υπογεγραμμένου εγγράφου με προστασία κωδικού.
Αυτή η ιδιότητα δεν υποστηρίζεται για έγγραφα εικόνας.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για την αποθήκευση του υπογεγραμμένου εγγράφου με προστασία κωδικού.
Αυτή η ιδιότητα δεν υποστηρίζεται για έγγραφα εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Λαμβάνει ή ορίζει αν θα χρησιμοποιηθεί ο κωδικός πρόσβασης από το LoadOptions για την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο.
Η προεπιλεγμένη τιμή είναι αληθής.
Αυτή η ιδιότητα δεν υποστηρίζεται για έγγραφα εικόνας.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Λαμβάνει ή ορίζει αν θα χρησιμοποιηθεί ο κωδικός πρόσβασης από το LoadOptions για την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο.
Η προεπιλεγμένη τιμή είναι αληθής.
Αυτή η ιδιότητα δεν υποστηρίζεται για έγγραφα εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Λαμβάνει ή ορίζει τη σημαία για αυτόματη προσθήκη επέκτασης όταν λείπει στη διαδρομή του αρχείου εξόδου.
Η προεπιλεγμένη τιμή είναι ψευδής.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για αυτόματη προσθήκη επέκτασης όταν λείπει στη διαδρομή του αρχείου εξόδου.
Η προεπιλεγμένη τιμή είναι ψευδής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

