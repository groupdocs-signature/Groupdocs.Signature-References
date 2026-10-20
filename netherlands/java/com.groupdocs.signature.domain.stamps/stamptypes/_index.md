---
title: "StampTypes"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Container voor stempeltypes."
type: docs
weight: 16
url: /nl/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Container voor stempeltypes.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Round](#Round) | Rond stempeltype-object. |
|
|  | [Square](#Square) | Vierkant stempeltype-object. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Alle stempeltypes. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Retourneert stempeltype met pasringType-naam. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Retourneert stempeltype met pasringType-naam. |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Rond stempeltype-object.


### Square {#Square}
```
public static final StampType Square
```


Vierkant stempeltype-object.


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Alle stempeltypes.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Retourneert stempeltype met pasringType-naam. Wanneer de naam van het stempel onbekend is - wordt een uitzondering gegooid.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | parsingType | java.lang.String | Bronstring van de naam van het stempeltype. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Retourneert stempeltype met pasringType-naam. Wanneer de naam van het stempel onbekend is - wordt er geen uitzondering gegooid en retourneert de methode een null-waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | parsingType | java.lang.String | Bronstring van de naam van het stempeltype. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

