---
title: "MetadataSignatureCollection"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Συλλογή αντικειμένων υπογραφής μεταδεδομένων."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Συλλογή αντικειμένων υπογραφής μεταδεδομένων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Δημιουργεί Συλλογή υπογραφής Metadata. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων στη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [contains(String name)](#contains-java.lang.String-) | Επιστρέφει true εάν υπάρχει ένα Metadata με το καθορισμένο όνομα στη συλλογή. |
| [indexOf(String name)](#indexOf-java.lang.String-) | Λαμβάνει τον δείκτη μιας ιδιότητας με βάση το όνομα. |
| [remove(String name)](#remove-java.lang.String-) | Αφαιρεί μια υπογραφή Metadata με το καθορισμένο όνομα από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί μια υπογραφή Metadata στον καθορισμένο δείκτη. |
| [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Προσθέτει αντικείμενο υπογραφής Metadata στη συλλογή. |
| [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Προσθέτει συλλογή υπογραφών Metadata. |
| [deepClone()](#deepClone--) | Κλωνοποιεί την κλάση Συλλογή υπογραφών Metadata με στοιχεία υπογραφών Metadata. |
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Δημιουργεί Συλλογή υπογραφής Metadata.

### getCount() {#getCount--}
```
public final int getCount()
```


Λαμβάνει τον αριθμό των στοιχείων στη συλλογή.

**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Επιστρέφει true εάν υπάρχει ένα Metadata με το καθορισμένο όνομα στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ιδιότητας χωρίς διάκριση πεζών-κεφαλαίων. |

**Returns:**
boolean - True εάν το Metadata υπάρχει στη συλλογή· false διαφορετικά.
### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Λαμβάνει τον δείκτη μιας ιδιότητας με βάση το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα του MetadataSignature χωρίς διάκριση πεζών-κεφαλαίων. |

**Returns:**
int - Ο δείκτης με βάση το μηδέν. Αρνητική τιμή εάν δεν βρεθεί.
### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Αφαιρεί μια υπογραφή Metadata με το καθορισμένο όνομα από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της υπογραφής Metadata χωρίς διάκριση πεζών-κεφαλαίων. |

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Αφαιρεί μια υπογραφή Metadata στον καθορισμένο δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Ο δείκτης με βάση το μηδέν. |

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Προσθέτει αντικείμενο υπογραφής Metadata στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Υπογραφή Metadata που θα προστεθεί στη συλλογή. |

--------------------

Κάνει throw εξαίρεση εάν η τιμή του ονόματος δεν είναι μοναδική σε ολόκληρη την υπάρχουσα συλλογή |

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Προσθέτει συλλογή υπογραφών Metadata.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Συλλογή υπογραφών προς προσθήκη. |

--------------------

Κάνει throw εξαίρεση εάν η τιμή του ονόματος δεν είναι μοναδική σε ολόκληρη την υπάρχουσα συλλογή |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Κλωνοποιεί την κλάση Συλλογή υπογραφών Metadata με στοιχεία υπογραφών Metadata.

**Returns:**
java.lang.Object - Επιστρέφει αντίγραφο της παρουσίας με κλωνοποιημένα στοιχεία υπογραφής
