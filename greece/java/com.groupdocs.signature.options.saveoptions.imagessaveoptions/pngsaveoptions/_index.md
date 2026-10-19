---
title: "PngSaveOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Επιλογές αποθήκευσης Png για έγγραφα εικόνας."
type: docs
weight: 22
url: /el/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

Επιλογές αποθήκευσης Png για έγγραφα εικόνας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PngSaveOptions()](#PngSaveOptions--) | Δημιουργεί το PngSaveOptions με προεπιλεγμένες τιμές. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getBitDepth()](#getBitDepth--) | Το βάθος bit. |
|
|  | [setBitDepth(byte value)](#setBitDepth-byte-) | Το βάθος bit. |
|
|  | [getColorType()](#getColorType--) | Αποκτά ή ορίζει τον τύπο του |
PngColorType
.
|
|  | [setColorType(int value)](#setColorType-int-) | Αποκτά ή ορίζει τον τύπο του |
PngColorType
.
|
|  | [getCompressionLevel()](#getCompressionLevel--) | Το επίπεδο συμπίεσης της εικόνας png στο εύρος 0-9, όπου το 9 είναι η μέγιστη συμπίεση |
και το 0 είναι λειτουργία αποθήκευσης.
|
|  | [setCompressionLevel(int value)](#setCompressionLevel-int-) | Το επίπεδο συμπίεσης της εικόνας png στο εύρος 0-9, όπου το 9 είναι η μέγιστη συμπίεση |
και το 0 είναι λειτουργία αποθήκευσης.
|
|  | [getFilterType()](#getFilterType--) | Αποκτά ή ορίζει τον τύπο φίλτρου |
PngFilterType
χρησιμοποιείται κατά τη διαδικασία αποθήκευσης του αρχείου png.
|
|  | [setFilterType(int value)](#setFilterType-int-) | Αποκτά ή ορίζει τον τύπο φίλτρου |
PngFilterType
χρησιμοποιείται κατά τη διαδικασία αποθήκευσης του αρχείου png.
|
|  | [getProgressive()](#getProgressive--) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το PngSaveOptions είναι προοδευτικό. |
|
|  | [setProgressive(boolean value)](#setProgressive-boolean-) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το PngSaveOptions είναι προοδευτικό. |
|
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


Δημιουργεί το PngSaveOptions με προεπιλεγμένες τιμές.


### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


Το βάθος bit.


**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


Το βάθος bit.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Αποκτά ή ορίζει τον τύπο του
PngColorType
.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Αποκτά ή ορίζει τον τύπο του
PngColorType
.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


Το επίπεδο συμπίεσης της εικόνας png στο εύρος 0-9, όπου το 9 είναι η μέγιστη συμπίεση
και το 0 είναι λειτουργία αποθήκευσης.


**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


Το επίπεδο συμπίεσης της εικόνας png στο εύρος 0-9, όπου το 9 είναι η μέγιστη συμπίεση
και το 0 είναι λειτουργία αποθήκευσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Αποκτά ή ορίζει τον τύπο φίλτρου
PngFilterType
χρησιμοποιείται κατά τη διαδικασία αποθήκευσης του αρχείου png.


**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Αποκτά ή ορίζει τον τύπο φίλτρου
PngFilterType
χρησιμοποιείται κατά τη διαδικασία αποθήκευσης του αρχείου png.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το PngSaveOptions είναι προοδευτικό.


**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το PngSaveOptions είναι προοδευτικό.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

