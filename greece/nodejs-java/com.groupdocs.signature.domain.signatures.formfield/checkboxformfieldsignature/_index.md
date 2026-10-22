---
title: "CheckboxFormFieldSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου τύπου check-box."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου τύπου check-box.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Δημιουργεί το PdfCheckboxFormFieldSignature με προκαθορισμένο όνομα. |
| [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Δημιουργεί το PdfCheckboxFormFieldSignature με προκαθορισμένο όνομα και τιμή. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChecked()](#getChecked--) | Λαμβάνει ή ορίζει την ελεγμένη τιμή της εισόδου πλαισίου ελέγχου πεδίου φόρμας. |
| [setChecked(boolean value)](#setChecked-boolean-) | Λαμβάνει ή ορίζει την ελεγμένη τιμή της εισόδου πλαισίου ελέγχου πεδίου φόρμας. |
| [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
| [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
| [deepClone()](#deepClone--) | Κλωνοποιεί το αντίγραφο της FormField Signature. |
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Δημιουργεί το PdfCheckboxFormFieldSignature με προκαθορισμένο όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Δημιουργεί το PdfCheckboxFormFieldSignature με προκαθορισμένο όνομα και τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
| isChecked | boolean | Τιμή εάν το πλαίσιο ελέγχου είναι επιλεγμένο. |

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Λαμβάνει ή ορίζει την ελεγμένη τιμή της εισόδου πλαισίου ελέγχου πεδίου φόρμας.

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Λαμβάνει ή ορίζει την ελεγμένη τιμή της εισόδου πλαισίου ελέγχου πεδίου φόρμας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| υπογραφή | java.lang.Object | Αντικείμενο υπογραφής για σύγκριση. |

**Returns:**
boolean - Επιστρέφει true εάν το δοσμένο αντικείμενο υπογραφής έχει τον ίδιο τύπο και όλες οι ιδιότητές του είναι ίσες με τις ιδιότητες αυτού του αντικειμένου.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Αντικαθιστά τη μέθοδο GetHashCode

**Returns:**
int - Κώδικας κατακερματισμού υπογραφής
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Κλωνοποιεί το αντίγραφο της FormField Signature.

**Returns:**
java.lang.Object - Επιστρέφει κλωνοποιημένη παρουσία υπογραφής FormField.
