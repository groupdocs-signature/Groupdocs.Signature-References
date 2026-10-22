---
title: "TextShadow"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει τις ιδιότητες σκιάς κειμένου για υπογραφές κειμένου."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Αντιπροσωπεύει τις ιδιότητες σκιάς κειμένου για υπογραφές κειμένου. Το αποτέλεσμα μπορεί να διαφέρει ανάλογα με τον τύπο της υπογραφής και τη μορφή του εγγράφου. Το TextShadow συνιστάται για χρήση με την υπογραφή TextAsImage για όλους τους υποστηριζόμενους τύπους εγγράφων, καθώς και με απλή TextSignature και TextSignature ως υδατογράφημα για Cells (.xslx) και Slides (.pptx). Απλή TextSignature για Words (.docx) συνιστάται επίσης, αλλά έχει περιορισμένη λειτουργικότητα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextShadow()](#TextShadow--) | Δημιουργεί TextShadow με προεπιλεγμένες επιλογές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDistance()](#getDistance--) | Λαμβάνει ή ορίζει την απόσταση από το κείμενο στη σκιά. |
| [setDistance(double value)](#setDistance-double-) | Λαμβάνει ή ορίζει την απόσταση από το κείμενο στη σκιά. |
| [getAngle()](#getAngle--) | Λαμβάνει ή ορίζει τη γωνία τοποθέτησης της σκιάς σε σχέση με το κείμενο. |
| [setAngle(double value)](#setAngle-double-) | Λαμβάνει ή ορίζει τη γωνία τοποθέτησης της σκιάς σε σχέση με το κείμενο. |
| [getColor()](#getColor--) | Λαμβάνει ή ορίζει το χρώμα της σκιάς. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Λαμβάνει ή ορίζει το χρώμα της σκιάς. |
| [setColor(String value)](#setColor-java.lang.String-) | Λαμβάνει ή ορίζει το χρώμα της σκιάς. |
| [getTransparency()](#getTransparency--) | Λαμβάνει ή ορίζει τη διαφάνεια της σκιάς. |
| [setTransparency(double value)](#setTransparency-double-) | Λαμβάνει ή ορίζει τη διαφάνεια της σκιάς. |
| [getBlur()](#getBlur--) | Λαμβάνει ή ορίζει την θόλωση της σκιάς. |
| [setBlur(double value)](#setBlur-double-) | Λαμβάνει ή ορίζει την θόλωση της σκιάς. |
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Δημιουργεί TextShadow με προεπιλεγμένες επιλογές.

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Λαμβάνει ή ορίζει την απόσταση από το κείμενο στη σκιά. Η προεπιλεγμένη τιμή είναι 1.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Λαμβάνει ή ορίζει την απόσταση από το κείμενο στη σκιά. Η προεπιλεγμένη τιμή είναι 1.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Λαμβάνει ή ορίζει τη γωνία τοποθέτησης της σκιάς σε σχέση με το κείμενο. Η προεπιλεγμένη τιμή είναι 0.

**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Λαμβάνει ή ορίζει τη γωνία τοποθέτησης της σκιάς σε σχέση με το κείμενο. Η προεπιλεγμένη τιμή είναι 0.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Λαμβάνει ή ορίζει το χρώμα της σκιάς. Η προεπιλεγμένη τιμή είναι Μαύρο.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα της σκιάς. Η προεπιλεγμένη τιμή είναι Μαύρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Λαμβάνει ή ορίζει το χρώμα της σκιάς. Η προεπιλεγμένη τιμή είναι Μαύρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Λαμβάνει ή ορίζει τη διαφάνεια της σκιάς. Η προεπιλεγμένη τιμή είναι 0.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Λαμβάνει ή ορίζει τη διαφάνεια της σκιάς. Η προεπιλεγμένη τιμή είναι 0.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Λαμβάνει ή ορίζει την θόλωση της σκιάς. Η προεπιλεγμένη τιμή είναι 4.

**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Λαμβάνει ή ορίζει την θόλωση της σκιάς. Η προεπιλεγμένη τιμή είναι 4.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

