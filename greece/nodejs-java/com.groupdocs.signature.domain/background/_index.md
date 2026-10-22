---
title: "Φόντο"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Αντιπροσωπεύει την εμφάνιση του φόντου"
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Αντιπροσωπεύει την εμφάνιση του φόντου
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Background()](#Background--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor()](#getColor--) | Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής. |
| [setColor(String value)](#setColor-java.lang.String-) | Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής. |
| [getTransparency()](#getTransparency--) | Λαμβάνει ή ορίζει τη διαφάνεια του φόντου (τιμή από 0.0 (αδιαφανές) έως 1.0 (διαυγές)). |
| [setTransparency(double value)](#setTransparency-double-) | Λαμβάνει ή ορίζει τη διαφάνεια του φόντου (τιμή από 0.0 (αδιαφανές) έως 1.0 (διαυγές)). |
| [getBrush()](#getBrush--) | Λαμβάνει ή ορίζει το πινέλο φόντου. |
| [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Λαμβάνει ή ορίζει το πινέλο φόντου. |
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Λαμβάνει ή ορίζει το χρώμα φόντου της υπογραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Λαμβάνει ή ορίζει τη διαφάνεια του φόντου (τιμή από 0.0 (αδιαφανές) έως 1.0 (διαυγές)).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Λαμβάνει ή ορίζει τη διαφάνεια του φόντου (τιμή από 0.0 (αδιαφανές) έως 1.0 (διαυγές)).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Λαμβάνει ή ορίζει το πινέλο φόντου. Η προεπιλεγμένη τιμή είναι null. Αυτή η ιδιότητα αναμένει μια παρουσία υλοποιήσεων αντικειμένων Brush. Δείτε διαφορετικές κλάσεις Brush.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Λαμβάνει ή ορίζει το πινέλο φόντου. Η προεπιλεγμένη τιμή είναι null. Αυτή η ιδιότητα αναμένει μια παρουσία υλοποιήσεων αντικειμένων Brush. Δείτε διαφορετικές κλάσεις Brush.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

