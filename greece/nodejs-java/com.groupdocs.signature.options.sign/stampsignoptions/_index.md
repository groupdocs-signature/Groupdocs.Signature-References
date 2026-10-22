---
title: "StampSignOptions"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει τις επιλογές υπογραφής σφραγίδας."
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Αντιπροσωπεύει τις επιλογές υπογραφής σφραγίδας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [StampSignOptions()](#StampSignOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης StampSignOptions με προεπιλεγμένες τιμές. |
| [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης StampSignOptions με επιλογές στοίχισης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getStampType()](#getStampType--) | Λαμβάνει ή ορίζει τον τύπο της σφραγίδας. |
| [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Λαμβάνει ή ορίζει τον τύπο της σφραγίδας. |
| [getOuterLines()](#getOuterLines--) | Λίστα εξωτερικών γραμμών που αποδίδονται ως συνελικτικοί κύκλοι. |
| [getInnerLines()](#getInnerLines--) | Λίστα εσωτερικών γραμμών που αποδίδονται ως σύνολο ορθογωνίων. |
| [getBackground()](#getBackground--) | Λαμβάνει ή ορίζει το φόντο της Σφραγίδας. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Λαμβάνει ή ορίζει το φόντο της Σφραγίδας. |
| [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής. |
| [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής. |
| [getBackgroundBrush()](#getBackgroundBrush--) | Λαμβάνει ή ορίζει το πινέλο φόντου της υπογραφής. |
| [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Λαμβάνει ή ορίζει το πινέλο φόντου της υπογραφής. |
| [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Λαμβάνει ή ορίζει τον τύπο περικοπής χρώματος φόντου της υπογραφής. |
| [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Λαμβάνει ή ορίζει τον τύπο περικοπής χρώματος φόντου της υπογραφής. |
| [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Λαμβάνει ή ορίζει τον τύπο περικοπής εικόνας φόντου της υπογραφής. |
| [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Λαμβάνει ή ορίζει τον τύπο περικοπής εικόνας φόντου της υπογραφής. |
| [toString()](#toString--) | Παράκαμψη μετατροπής συμβολοσειράς |
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης StampSignOptions με προεπιλεγμένες τιμές.

### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης StampSignOptions με επιλογές στοίχισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριστερά | int | Η συντεταγμένη x του αριστερού άνω άκρου της υπογραφής σφραγίδας |
| επάνω | int | Η συντεταγμένη y του αριστερού άνω άκρου της υπογραφής σφραγίδας |
| πλάτος | int | Το πλάτος της υπογραφής σφραγίδας |
| ύψος | int | Το ύψος της υπογραφής σφραγίδας |

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Λαμβάνει ή ορίζει τον τύπο σφραγίδας. Η προεπιλεγμένη τιμή είναι Στρογγυλή.

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Λαμβάνει ή ορίζει τον τύπο σφραγίδας. Η προεπιλεγμένη τιμή είναι Στρογγυλή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Λίστα εξωτερικών γραμμών που αποδίδονται ως συνελικτικοί κύκλοι.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


Λίστα εσωτερικών γραμμών που αποδίδονται ως σύνολο ορθογωνίων.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Λαμβάνει ή ορίζει το φόντο της Σφραγίδας.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Λαμβάνει ή ορίζει το φόντο της Σφραγίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής.

**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Λαμβάνει ή ορίζει το πινέλο φόντου της υπογραφής. Η προεπιλεγμένη τιμή είναι null.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Λαμβάνει ή ορίζει το πινέλο φόντου της υπογραφής. Η προεπιλεγμένη τιμή είναι null.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Λαμβάνει ή ορίζει τον τύπο περικοπής χρώματος φόντου της υπογραφής.

**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Λαμβάνει ή ορίζει τον τύπο περικοπής χρώματος φόντου της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Λαμβάνει ή ορίζει τον τύπο περικοπής εικόνας φόντου της υπογραφής.

**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Λαμβάνει ή ορίζει τον τύπο περικοπής εικόνας φόντου της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Παράκαμψη μετατροπής συμβολοσειράς

**Returns:**
java.lang.String -
