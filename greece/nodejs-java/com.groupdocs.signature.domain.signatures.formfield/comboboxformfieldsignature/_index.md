---
title: "ComboboxFormFieldSignature"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου τύπου combo-box."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Περιέχει ιδιότητες υπογραφής πεδίου φόρμας εισόδου τύπου combo-box.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Δημιουργεί ComboboxFormFieldSignature με προκαθορισμένο όνομα. |
| [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Δημιουργεί ComboboxFormFieldSignature με προκαθορισμένο όνομα και λίστα επιλογών. |
| [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Δημιουργεί ComboboxFormFieldSignature με προκαθορισμένο όνομα, λίστα επιλογών και επιλεγμένη τιμή. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSelected()](#getSelected--) | Λάβετε ή ορίστε την επιλεγμένη τιμή. |
| [setSelected(String value)](#setSelected-java.lang.String-) | Λάβετε ή ορίστε την επιλεγμένη τιμή. |
| [getItems()](#getItems--) | Λάβετε ή ορίστε τη λίστα επιλογών combo-box. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Λάβετε ή ορίστε τη λίστα επιλογών combo-box. |
| [equals(Object signature)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο Equals για τη σύγκριση των ιδιοτήτων της υπογραφής. |
| [hashCode()](#hashCode--) | Αντικαθιστά τη μέθοδο GetHashCode |
| [deepClone()](#deepClone--) | Κλωνοποιεί το αντίγραφο της FormField Signature. |
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Δημιουργεί ComboboxFormFieldSignature με προκαθορισμένο όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Δημιουργεί ComboboxFormFieldSignature με προκαθορισμένο όνομα και λίστα επιλογών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
| αντικείμενα | java.util.List<java.lang.String> | Τιμές της λίστας combo-box. |

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Δημιουργεί ComboboxFormFieldSignature με προκαθορισμένο όνομα, λίστα επιλογών και επιλεγμένη τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα του αντικειμένου πεδίου φόρμας. |
| αντικείμενα | java.util.List<java.lang.String> | Τιμές της λίστας combo-box. |
| επιλεγμένο | java.lang.Object | Επιλεγμένη τιμή. |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Λάβετε ή ορίστε την επιλεγμένη τιμή.

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Λάβετε ή ορίστε την επιλεγμένη τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Λάβετε ή ορίστε τη λίστα επιλογών combo-box.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Λάβετε ή ορίστε τη λίστα επιλογών combo-box.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<java.lang.String> |  |

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
