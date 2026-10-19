---
title: "BmpSaveOptions"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Επιλογές αποθήκευσης Bmp για έγγραφα εικόνας."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bmpsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class BmpSaveOptions extends ImageSaveOptions
```

Επιλογές αποθήκευσης Bmp για έγγραφα εικόνας.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [BmpSaveOptions()](#BmpSaveOptions--) | Δημιουργεί BmpSaveOptions με προεπιλεγμένες τιμές. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getBitsPerPixel()](#getBitsPerPixel--) | Λαμβάνει ή ορίζει τον αριθμό bits ανά pixel της εικόνας. |
|
|  | [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Λαμβάνει ή ορίζει τον αριθμό bits ανά pixel της εικόνας. |
|
|  | [getCompression()](#getCompression--) | Λαμβάνει ή ορίζει τη συμπίεση. |
|
|  | [setCompression(int value)](#setCompression-int-) | Λαμβάνει ή ορίζει τη συμπίεση. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Λαμβάνει ή ορίζει την οριζόντια ανάλυση. |
|
|  | [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Λαμβάνει ή ορίζει την οριζόντια ανάλυση. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Λαμβάνει ή ορίζει την κάθετη ανάλυση. |
|
|  | [setVerticalResolution(double value)](#setVerticalResolution-double-) | Λαμβάνει ή ορίζει την κάθετη ανάλυση. |
|
### BmpSaveOptions() {#BmpSaveOptions--}
```
public BmpSaveOptions()
```


Δημιουργεί BmpSaveOptions με προεπιλεγμένες τιμές.


### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


Λαμβάνει ή ορίζει τον αριθμό bits ανά pixel της εικόνας.


**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


Λαμβάνει ή ορίζει τον αριθμό bits ανά pixel της εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


Λαμβάνει ή ορίζει τη συμπίεση. Δείτε [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression).


**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


Λαμβάνει ή ορίζει τη συμπίεση. Δείτε [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final double getHorizontalResolution()
```


Λαμβάνει ή ορίζει την οριζόντια ανάλυση. Σημειώστε ότι λόγω στρογγυλοποίησης το αποτέλεσμα
η ανάλυση μπορεί να διαφέρει ελαφρώς από αυτή που δόθηκε.


**Returns:**
double
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public final void setHorizontalResolution(double value)
```


Λαμβάνει ή ορίζει την οριζόντια ανάλυση. Σημειώστε ότι λόγω στρογγυλοποίησης το αποτέλεσμα
η ανάλυση μπορεί να διαφέρει ελαφρώς από αυτή που δόθηκε.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final double getVerticalResolution()
```


Λαμβάνει ή ορίζει την κάθετη ανάλυση. Σημειώστε ότι λόγω στρογγυλοποίησης το αποτέλεσμα
η ανάλυση μπορεί να διαφέρει ελαφρώς από αυτή που δόθηκε.


**Returns:**
double
### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public final void setVerticalResolution(double value)
```


Λαμβάνει ή ορίζει την κάθετη ανάλυση. Σημειώστε ότι λόγω στρογγυλοποίησης το αποτέλεσμα
η ανάλυση μπορεί να διαφέρει ελαφρώς από αυτή που δόθηκε.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

