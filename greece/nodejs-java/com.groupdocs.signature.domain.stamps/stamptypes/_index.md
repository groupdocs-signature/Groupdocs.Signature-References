---
title: "StampTypes"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Δοχείο τύπων σφραγίδας."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Δοχείο τύπων σφραγίδας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Round](#Round) | Αντικείμενο τύπου στρογγυλής σφραγίδας. |
| [Square](#Square) | Αντικείμενο τύπου τετράγωνης σφραγίδας. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | Όλοι οι τύποι σφραγίδας. |
| [parse(String parsingType)](#parse-java.lang.String-) | Επιστρέφει τύπο σφραγίδας με το όνομα pasringType. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | Επιστρέφει τύπο σφραγίδας με το όνομα pasringType. |
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Αντικείμενο τύπου στρογγυλής σφραγίδας.

### Square {#Square}
```
public static final StampType Square
```


Αντικείμενο τύπου τετράγωνης σφραγίδας.

### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Όλοι οι τύποι σφραγίδας.

**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Επιστρέφει τύπο σφραγίδας με το όνομα pasringType. Όταν το όνομα της σφραγίδας είναι άγνωστο - ρίχνεται εξαίρεση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Συμβολοσειρά πηγής του ονόματος τύπου σφραγίδας. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Επιστρέφει τύπο σφραγίδας με το όνομα pasringType. Όταν το όνομα της σφραγίδας είναι άγνωστο - δεν ρίχνεται εξαίρεση και η μέθοδος επιστρέφει τιμή null.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Συμβολοσειρά πηγής του ονόματος τύπου σφραγίδας. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
