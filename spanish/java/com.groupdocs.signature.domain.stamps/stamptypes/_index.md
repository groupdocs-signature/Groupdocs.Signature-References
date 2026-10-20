---
title: "StampTypes"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contenedor de tipos de sello."
type: docs
weight: 16
url: /es/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Contenedor de tipos de sello.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Round](#Round) | Objeto de tipo de sello redondo. |
|
|  | [Square](#Square) | Objeto de tipo de sello cuadrado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Todos los tipos de sello. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Devuelve el tipo de sello con el nombre pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Devuelve el tipo de sello con el nombre pasringType. |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Objeto de tipo de sello redondo.


### Square {#Square}
```
public static final StampType Square
```


Objeto de tipo de sello cuadrado.


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Todos los tipos de sello.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Devuelve el tipo de sello con el nombre pasringType. Cuando el nombre del sello es desconocido, se lanza una excepción.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | parsingType | java.lang.String | Cadena origen del nombre del tipo de sello. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Devuelve el tipo de sello con el nombre pasringType. Cuando el nombre del sello es desconocido, no se lanza ninguna excepción y el método devuelve un valor nulo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | parsingType | java.lang.String | Cadena origen del nombre del tipo de sello. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

