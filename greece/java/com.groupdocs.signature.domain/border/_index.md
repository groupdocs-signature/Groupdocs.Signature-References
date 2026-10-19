---
title: "Πλαίσιο"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Παράδειγμα για διατήρηση ιδιοτήτων γραμμής περιγράμματος."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Παράδειγμα για διατήρηση ιδιοτήτων γραμμής περιγράμματος.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Border()](#Border--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | Λαμβάνει ή ορίζει το στυλ του πλαισίου της υπογραφής. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Λαμβάνει ή ορίζει το στυλ του πλαισίου της υπογραφής. |
|
|  | [getTransparency()](#getTransparency--) | Λαμβάνει ή ορίζει τη διαφάνεια του πλαισίου της υπογραφής (τιμή από 0.0 (αδιαφανές) έως 1.0 (διαυγές)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Λαμβάνει ή ορίζει τη διαφάνεια του πλαισίου της υπογραφής (τιμή από 0.0 (αδιαφανές) έως 1.0 (διαυγές)). |
|
|  | [getWeight()](#getWeight--) | Λαμβάνει ή ορίζει το βάρος του πλαισίου της υπογραφής. |
|
|  | [setWeight(double value)](#setWeight-double-) | Λαμβάνει ή ορίζει το βάρος του πλαισίου της υπογραφής. |
|
|  | [getColor()](#getColor--) | Λαμβάνει ή ορίζει το χρώμα του πλαισίου της υπογραφής. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Λαμβάνει ή ορίζει το χρώμα του πλαισίου της υπογραφής. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Λαμβάνει ή ορίζει το χρώμα του πλαισίου της υπογραφής. |
|
|  | [getVisible()](#getVisible--) | Λαμβάνει ή ορίζει την ορατότητα του πλαισίου. |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | Υλοποιήστε τη διεπαφή IClonable |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Λαμβάνει ή ορίζει το στυλ του πλαισίου της υπογραφής.


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Λαμβάνει ή ορίζει το στυλ του πλαισίου της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Λαμβάνει ή ορίζει τη διαφάνεια του πλαισίου της υπογραφής (τιμή από 0.0 (αδιαφανές) έως 1.0 (διαυγές)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Λαμβάνει ή ορίζει τη διαφάνεια του πλαισίου της υπογραφής (τιμή από 0.0 (αδιαφανές) έως 1.0 (διαυγές)).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Λαμβάνει ή ορίζει το βάρος του πλαισίου της υπογραφής.


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Λαμβάνει ή ορίζει το βάρος του πλαισίου της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Λαμβάνει ή ορίζει το χρώμα του πλαισίου της υπογραφής.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα του πλαισίου της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Λαμβάνει ή ορίζει το χρώμα του πλαισίου της υπογραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Λαμβάνει ή ορίζει την ορατότητα του πλαισίου.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Υλοποιήστε τη διεπαφή IClonable


**Returns:**
java.lang.Object - Νέα δημιουργημένη παρουσία Border με τις ίδιες ιδιότητες

