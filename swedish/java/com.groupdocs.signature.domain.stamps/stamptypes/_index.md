---
title: "StampTypes"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Behållare för stämpeltyper."
type: docs
weight: 16
url: /sv/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Behållare för stämpeltyper.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Round](#Round) | Rund stämpeltypobjekt. |
|
|  | [Square](#Square) | Fyrkantig stämpeltypobjekt. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Alla stämpeltyper. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Returnerar stämpeltyp med pasringType-namn. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Returnerar stämpeltyp med pasringType-namn. |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Rund stämpeltypobjekt.


### Square {#Square}
```
public static final StampType Square
```


Fyrkantig stämpeltypobjekt.


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Alla stämpeltyper.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Returnerar stämpeltyp med pasringType-namn. När stämpelns namn är okänt - ett undantag kastas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | parsingType | java.lang.String | Källsträng för stämpeltypens namn. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Returnerar stämpeltyp med pasringType-namn. När stämpelns namn är okänt - kastas inget undantag och metoden returnerar nullvärde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | parsingType | java.lang.String | Källsträng för stämpeltypens namn. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

