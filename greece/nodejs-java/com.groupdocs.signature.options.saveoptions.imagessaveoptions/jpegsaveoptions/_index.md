---
title: "JpegSaveOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Επιλογές αποθήκευσης Jpeg για έγγραφα εικόνας."
type: docs
weight: 19
url: /el/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Επιλογές αποθήκευσης Jpeg για έγγραφα εικόνας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [JpegSaveOptions()](#JpegSaveOptions--) | Δημιουργεί το JpegSaveOptions με προεπιλεγμένες τιμές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBitsPerChannel()](#getBitsPerChannel--) | Λαμβάνει ή ορίζει τα bits ανά κανάλι για εικόνα jpeg χωρίς απώλειες. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Λαμβάνει ή ορίζει τα bits ανά κανάλι για εικόνα jpeg χωρίς απώλειες. |
| [getColorType()](#getColorType--) | Λαμβάνει ή ορίζει τον τύπο χρώματος για εικόνα jpeg. |
| [setColorType(int value)](#setColorType-int-) | Λαμβάνει ή ορίζει τον τύπο χρώματος για εικόνα jpeg. |
| [getComment()](#getComment--) | Λαμβάνει ή ορίζει το σχόλιο αρχείου jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | Λαμβάνει ή ορίζει το σχόλιο αρχείου jpeg. |
| [getCompressionType()](#getCompressionType--) | Λαμβάνει ή ορίζει τον τύπο συμπίεσης. |
| [setCompressionType(int value)](#setCompressionType-int-) | Λαμβάνει ή ορίζει τον τύπο συμπίεσης. |
| [getQuality()](#getQuality--) | Λαμβάνει ή ορίζει την ποιότητα εικόνας. |
| [setQuality(int value)](#setQuality-int-) | Λαμβάνει ή ορίζει την ποιότητα εικόνας. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Λαμβάνει ή ορίζει τη λειτουργία στρογγυλοποίησης δείγματος για να ταιριάζει μια τιμή 8-bit σε τιμή n-bit JpegOptions.BitsPerChannel. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Λαμβάνει ή ορίζει τη λειτουργία στρογγυλοποίησης δείγματος για να ταιριάζει μια τιμή 8-bit σε τιμή n-bit JpegOptions.BitsPerChannel. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
| [setFileFormat(int value)](#setFileFormat-int-) | Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. |
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Δημιουργεί το JpegSaveOptions με προεπιλεγμένες τιμές.

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Λαμβάνει ή ορίζει τα bits ανά κανάλι για εικόνα jpeg χωρίς απώλειες. Τώρα υποστηρίζουμε από 2 έως 8 bits ανά κανάλι.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Λαμβάνει ή ορίζει τα bits ανά κανάλι για εικόνα jpeg χωρίς απώλειες. Τώρα υποστηρίζουμε από 2 έως 8 bits ανά κανάλι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Λαμβάνει ή ορίζει τον τύπο χρώματος για εικόνα jpeg.

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Λαμβάνει ή ορίζει τον τύπο χρώματος για εικόνα jpeg.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Λαμβάνει ή ορίζει το σχόλιο αρχείου jpeg.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Λαμβάνει ή ορίζει το σχόλιο αρχείου jpeg.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Λαμβάνει ή ορίζει τον τύπο συμπίεσης.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Λαμβάνει ή ορίζει τον τύπο συμπίεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Λαμβάνει ή ορίζει την ποιότητα εικόνας.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Λαμβάνει ή ορίζει την ποιότητα εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Λαμβάνει ή ορίζει τη λειτουργία στρογγυλοποίησης δείγματος για να ταιριάζει μια τιμή 8-bit σε τιμή n-bit JpegOptions.BitsPerChannel.

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Λαμβάνει ή ορίζει τη λειτουργία στρογγυλοποίησης δείγματος για να ταιριάζει μια τιμή 8-bit σε τιμή n-bit JpegOptions.BitsPerChannel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. Κρυφό επειδή δεν χρησιμοποιείται για αυτήν την κλάση επιλογών.

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Λαμβάνει ή ορίζει τη μορφή αρχείου του υπογεγραμμένου εγγράφου. Κρυφό επειδή δεν χρησιμοποιείται για αυτήν την κλάση επιλογών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

