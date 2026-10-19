---
title: "MetadataSignatureCollection"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Συλλογή αντικειμένων υπογραφής μεταδεδομένων."
type: docs
weight: 13
url: /el/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
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
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Δημιουργεί Συλλογή υπογραφής Metadata. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων στη συλλογή. |
|
|  | [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
|
|  | [contains(String name)](#contains-java.lang.String-) | Επιστρέφει true εάν υπάρχει Metadata με το καθορισμένο όνομα στη συλλογή. |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | Λαμβάνει το ευρετήριο μιας ιδιότητας με βάση το όνομα. |
|
|  | [remove(String name)](#remove-java.lang.String-) | Αφαιρεί ένα Metadata Signature με το καθορισμένο όνομα από τη συλλογή. |
|
|  | [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα Metadata Signature στο καθορισμένο ευρετήριο. |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Προσθέτει αντικείμενο Metadata Signature στη συλλογή. |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Προσθέτει συλλογή Metadata Signature. |
|
|  | [deepClone()](#deepClone--) | Κλωνοποιεί την κλάση Metadata Signature Collection με στοιχεία Metadata Signature. |
|
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


Επιστρέφει true εάν υπάρχει Metadata με το καθορισμένο όνομα στη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το όνομα της ιδιότητας χωρίς διάκριση πεζών-κεφαλαίων. |
|

**Returns:**
boolean - True εάν το Metadata υπάρχει στη συλλογή· false διαφορετικά.

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Λαμβάνει το ευρετήριο μιας ιδιότητας με βάση το όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το όνομα του MetadataSignature χωρίς διάκριση πεζών-κεφαλαίων. |
|

**Returns:**
int - Το μηδενικό ευρετήριο. Αρνητική τιμή εάν δεν βρεθεί.

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Αφαιρεί ένα Metadata Signature με το καθορισμένο όνομα από τη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το όνομα του Metadata Signature χωρίς διάκριση πεζών-κεφαλαίων. |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Αφαιρεί ένα Metadata Signature στο καθορισμένο ευρετήριο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ευρετήριο | int | Το μηδενικό ευρετήριο. |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Προσθέτει αντικείμενο Metadata Signature στη συλλογή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Υπογραφή Metadata που θα προστεθεί στη συλλογή. |

<br />

*** ** * ** ***

Ρίχνει εξαίρεση εάν η τιμή του ονόματος δεν είναι μοναδική σε ολόκληρη την υπάρχουσα συλλογή

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Προσθέτει συλλογή Metadata Signature.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Συλλογή υπογραφών προς προσθήκη. |

<br />

*** ** * ** ***

Ρίχνει εξαίρεση εάν η τιμή του ονόματος δεν είναι μοναδική σε ολόκληρη την υπάρχουσα συλλογή

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Κλωνοποιεί την κλάση Metadata Signature Collection με στοιχεία Metadata Signature.


**Returns:**
java.lang.Object - Επιστρέφει αντίγραφο του αντικειμένου με κλωνοποιημένα στοιχεία Signature.

