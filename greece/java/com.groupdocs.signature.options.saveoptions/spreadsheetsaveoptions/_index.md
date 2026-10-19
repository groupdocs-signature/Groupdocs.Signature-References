---
title: "SpreadsheetSaveOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Επιλογές αποθήκευσης για έγγραφα Φύλλων Εργασίας."
type: docs
weight: 14
url: /el/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Επιλογές αποθήκευσης για έγγραφα Φύλλων Εργασίας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Αρχικοποιεί ένα νέο αντίγραφο της κλάσης SpreadsheetSaveOptions με προεπιλεγμένες τιμές. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Αρχικοποιεί ένα νέο αντίγραφο της κλάσης SpreadsheetSaveOptions με προκαθορισμένη μορφή αρχείου εξόδου. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Αρχικοποιεί ένα νέο αντίγραφο της κλάσης SpreadsheetSaveOptions με καθορισμένο τύπο εξόδου και σημαία αντικατάστασης. |
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
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Αρχικοποιεί ένα νέο αντίγραφο της κλάσης SpreadsheetSaveOptions με προεπιλεγμένες τιμές.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Αρχικοποιεί ένα νέο αντίγραφο της κλάσης SpreadsheetSaveOptions με προκαθορισμένη μορφή αρχείου εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileFormat | int | Καθορίζει τη μορφή αρχείου εξόδου. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Αρχικοποιεί ένα νέο αντίγραφο της κλάσης SpreadsheetSaveOptions με καθορισμένο τύπο εξόδου και σημαία αντικατάστασης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileFormat | int | Καθορίζει τη μορφή αρχείου εξόδου. |
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
