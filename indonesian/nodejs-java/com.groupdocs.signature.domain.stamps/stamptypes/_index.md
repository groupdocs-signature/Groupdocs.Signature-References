---
title: "StampTypes"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Kontainer tipe stempel."
type: docs
weight: 16
url: /id/nodejs-java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Kontainer tipe stempel.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Round](#Round) | Objek tipe stempel bulat. |
| [Square](#Square) | Objek tipe stempel persegi. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | Semua tipe stempel. |
| [parse(String parsingType)](#parse-java.lang.String-) | Mengembalikan tipe stempel dengan nama pasringType. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | Mengembalikan tipe stempel dengan nama pasringType. |
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Objek tipe stempel bulat.

### Square {#Square}
```
public static final StampType Square
```


Objek tipe stempel persegi.

### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Semua tipe stempel.

**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Mengembalikan tipe stempel dengan nama pasringType. Ketika nama stempel tidak diketahui - pengecualian dilempar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | String sumber nama tipe stempel. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Mengembalikan tipe stempel dengan nama pasringType. Ketika nama stempel tidak diketahui - tidak ada pengecualian yang dilempar dan metode mengembalikan nilai null.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | String sumber nama tipe stempel. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
