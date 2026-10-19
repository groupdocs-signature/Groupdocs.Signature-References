---
title: "StampTypes"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Conteneur de types de tampons."
type: docs
weight: 16
url: /fr/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Conteneur de types de tampons.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [Round](#Round) | Objet de type de tampon rond. |
|
|  | [Square](#Square) | Objet de type de tampon carré. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Tous les types de tampon. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Renvoie le type de tampon avec le nom pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Renvoie le type de tampon avec le nom pasringType. |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Objet de type de tampon rond.


### Square {#Square}
```
public static final StampType Square
```


Objet de type de tampon carré.


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Tous les types de tampon.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Renvoie le type de tampon avec le nom pasringType. Lorsque le nom du tampon est inconnu - une exception est levée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | parsingType | java.lang.String | Chaîne source du nom du type de tampon. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Renvoie le type de tampon avec le nom pasringType. Lorsque le nom du tampon est inconnu - aucune exception n'est levée et la méthode renvoie une valeur null.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | parsingType | java.lang.String | Chaîne source du nom du type de tampon. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

