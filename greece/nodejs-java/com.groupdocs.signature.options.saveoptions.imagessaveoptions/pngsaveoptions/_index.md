---
title: "PngSaveOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Επιλογές αποθήκευσης Png για έγγραφα εικόνας."
type: docs
weight: 22
url: /el/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
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
| [PngSaveOptions()](#PngSaveOptions--) | Δημιουργεί το PngSaveOptions με προεπιλεγμένες τιμές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBitDepth()](#getBitDepth--) | Το βάθος χρώματος. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Το βάθος χρώματος. |
| [getColorType()](#getColorType--) | Λαμβάνει ή ορίζει τον τύπο του  PngColorType . |
| [setColorType(int value)](#setColorType-int-) | Λαμβάνει ή ορίζει τον τύπο του  PngColorType . |
| [getCompressionLevel()](#getCompressionLevel--) | Το επίπεδο συμπίεσης εικόνας png στην κλίμακα 0-9, όπου το 9 είναι μέγιστη συμπίεση και το 0 είναι λειτουργία αποθήκευσης. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Το επίπεδο συμπίεσης εικόνας png στην κλίμακα 0-9, όπου το 9 είναι μέγιστη συμπίεση και το 0 είναι λειτουργία αποθήκευσης. |
| [getFilterType()](#getFilterType--) | Λαμβάνει ή ορίζει τον τύπο φίλτρου  PngFilterType  που χρησιμοποιείται κατά τη διαδικασία αποθήκευσης αρχείου png. |
| [setFilterType(int value)](#setFilterType-int-) | Λαμβάνει ή ορίζει τον τύπο φίλτρου  PngFilterType  που χρησιμοποιείται κατά τη διαδικασία αποθήκευσης αρχείου png. |
| [getProgressive()](#getProgressive--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το PngSaveOptions είναι προοδευτικό. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το PngSaveOptions είναι προοδευτικό. |
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


Δημιουργεί το PngSaveOptions με προεπιλεγμένες τιμές.

### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


Το βάθος χρώματος.

**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


Το βάθος χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Λαμβάνει ή ορίζει τον τύπο του  PngColorType .

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Λαμβάνει ή ορίζει τον τύπο του  PngColorType .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


Το επίπεδο συμπίεσης εικόνας png στην κλίμακα 0-9, όπου το 9 είναι μέγιστη συμπίεση και το 0 είναι λειτουργία αποθήκευσης.

**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


Το επίπεδο συμπίεσης εικόνας png στην κλίμακα 0-9, όπου το 9 είναι μέγιστη συμπίεση και το 0 είναι λειτουργία αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Λαμβάνει ή ορίζει τον τύπο φίλτρου  PngFilterType  που χρησιμοποιείται κατά τη διαδικασία αποθήκευσης αρχείου png.

**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Λαμβάνει ή ορίζει τον τύπο φίλτρου  PngFilterType  που χρησιμοποιείται κατά τη διαδικασία αποθήκευσης αρχείου png.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το PngSaveOptions είναι προοδευτικό.

**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το PngSaveOptions είναι προοδευτικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

