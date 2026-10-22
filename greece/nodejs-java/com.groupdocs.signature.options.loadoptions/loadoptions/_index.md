---
title: "LoadOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Επιτρέπει τον καθορισμό πρόσθετων επιλογών, όπως κωδικός πρόσβασης, κατά το άνοιγμα εγγράφου για υπογραφή."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως κωδικός) κατά το άνοιγμα εγγράφου για υπογραφή.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης LoadOptions. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPassword()](#getPassword--) | Λαμβάνει ή ορίζει κωδικό πρόσβασης για το άνοιγμα προστατευμένου εγγράφου. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Λαμβάνει ή ορίζει κωδικό πρόσβασης για το άνοιγμα προστατευμένου εγγράφου. |
| [getLoadExternalResources()](#getLoadExternalResources--) | Λαμβάνει ή ορίζει επιλογές που καθορίζουν εάν πρέπει να φορτωθούν εξωτερικοί πόροι εγγράφου. |
| [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Λαμβάνει ή ορίζει επιλογές που καθορίζουν εάν πρέπει να φορτωθούν εξωτερικοί πόροι εγγράφου. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης LoadOptions.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Λαμβάνει ή ορίζει κωδικό πρόσβασης για το άνοιγμα προστατευμένου εγγράφου. Θα χρησιμοποιηθεί επίσης για την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Λαμβάνει ή ορίζει κωδικό πρόσβασης για το άνοιγμα προστατευμένου εγγράφου. Θα χρησιμοποιηθεί επίσης για την αποθήκευση του υπογεγραμμένου εγγράφου ως προστατευμένο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Λαμβάνει ή ορίζει επιλογές που καθορίζουν εάν πρέπει να φορτωθούν εξωτερικοί πόροι εγγράφου. Αυτή η επιλογή με απενεργοποιημένη τιμή (false) επιτρέπει την εξοικονόμηση χρόνου φόρτωσης για έγγραφα με πολλούς ή μεγάλους εξωτερικούς συνδέσμους πόρων. Η προεπιλεγμένη τιμή είναι ενεργοποιημένη (true).

**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Λαμβάνει ή ορίζει επιλογές που καθορίζουν εάν πρέπει να φορτωθούν εξωτερικοί πόροι εγγράφου. Αυτή η επιλογή με απενεργοποιημένη τιμή (false) επιτρέπει την εξοικονόμηση χρόνου φόρτωσης για έγγραφα με πολλούς ή μεγάλους εξωτερικούς συνδέσμους πόρων. Η προεπιλεγμένη τιμή είναι ενεργοποιημένη (true).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

