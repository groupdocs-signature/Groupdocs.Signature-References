---
title: "LoadOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Επιτρέπει τον καθορισμό πρόσθετων επιλογών όπως κωδικός πρόσβασης κατά το άνοιγμα ενός εγγράφου για υπογραφή."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως κωδικός πρόσβασης) κατά το άνοιγμα ενός εγγράφου για υπογραφή.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης LoadOptions. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για το άνοιγμα ενός προστατευμένου εγγράφου. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για το άνοιγμα ενός προστατευμένου εγγράφου. |
|
|  | [getLoadExternalResources()](#getLoadExternalResources--) | Λαμβάνει ή ορίζει επιλογές που καθορίζουν εάν πρέπει να φορτωθούν εξωτερικοί πόροι εγγράφου. |
|
|  | [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Λαμβάνει ή ορίζει επιλογές που καθορίζουν εάν πρέπει να φορτωθούν εξωτερικοί πόροι εγγράφου. |
|
|  | [getPermissions()](#getPermissions--) | Τα δικαιώματα του εγγράφου PDF όπως η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Εσωτερικός setter, που χρησιμοποιείται από επεξεργαστές φόρτωσης εγγράφων για την καταγραφή των δικαιωμάτων που αναλύθηκαν από το αρχείο. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης LoadOptions.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για το άνοιγμα ενός προστατευμένου εγγράφου.
Θα χρησιμοποιηθεί επίσης για την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Λαμβάνει ή ορίζει τον κωδικό πρόσβασης για το άνοιγμα ενός προστατευμένου εγγράφου.
Θα χρησιμοποιηθεί επίσης για την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Λαμβάνει ή ορίζει επιλογές που καθορίζουν εάν πρέπει να φορτωθούν εξωτερικοί πόροι εγγράφου.
Αυτή η επιλογή με απενεργοποιημένη τιμή (false) επιτρέπει τη μείωση του χρόνου φόρτωσης για έγγραφα με πολλούς ή μεγάλους συνδέσμους εξωτερικών πόρων.
Η προεπιλεγμένη τιμή είναι ενεργοποιημένη (true).


**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Λαμβάνει ή ορίζει επιλογές που καθορίζουν εάν πρέπει να φορτωθούν εξωτερικοί πόροι εγγράφου.
Αυτή η επιλογή με απενεργοποιημένη τιμή (false) επιτρέπει τη μείωση του χρόνου φόρτωσης για έγγραφα με πολλούς ή μεγάλους συνδέσμους εξωτερικών πόρων.
Η προεπιλεγμένη τιμή είναι ενεργοποιημένη (true).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Τα δικαιώματα του εγγράφου PDF όπως η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων.
Μόνο για έγγραφα PDF. Μόνο για ανάγνωση \\u2014 γεμίζει αυτόματα κατά τη φόρτωση του εγγράφου.
Η τιμή είναι ένας συνδυασμός σημαιών από [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Εσωτερικός setter, που χρησιμοποιείται από επεξεργαστές φόρτωσης εγγράφων για την καταγραφή των δικαιωμάτων που αναλύθηκαν από το αρχείο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Integer |  |

