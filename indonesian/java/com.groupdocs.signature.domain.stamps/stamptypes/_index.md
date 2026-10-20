---
title: "StampTypes"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Kontainer jenis-jenis stempel."
type: docs
weight: 16
url: /id/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Kontainer jenis-jenis stempel.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Round](#Round) | Objek tipe cap bulat. |
|
|  | [Square](#Square) | Objek tipe cap persegi. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Semua tipe cap. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Mengembalikan tipe cap dengan nama pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Mengembalikan tipe cap dengan nama pasringType. |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Objek tipe cap bulat.


### Square {#Square}
```
public static final StampType Square
```


Objek tipe cap persegi.


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Semua tipe cap.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Mengembalikan tipe cap dengan nama pasringType. Ketika nama cap tidak diketahui - pengecualian dilempar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | parsingType | java.lang.String | String sumber nama tipe cap. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Mengembalikan tipe cap dengan nama pasringType. Ketika nama cap tidak diketahui - tidak ada pengecualian yang dilempar dan metode mengembalikan nilai null.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | parsingType | java.lang.String | String sumber nama tipe cap. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

