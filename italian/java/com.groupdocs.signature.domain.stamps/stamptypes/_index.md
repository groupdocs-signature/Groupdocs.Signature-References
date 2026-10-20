---
title: "StampTypes"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Contenitore dei tipi di timbro."
type: docs
weight: 16
url: /it/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Contenitore dei tipi di timbro.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Round](#Round) | Oggetto tipo timbro rotondo. |
|
|  | [Square](#Square) | Oggetto tipo timbro quadrato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Tutti i tipi di timbro. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Restituisce il tipo di timbro con il nome pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Restituisce il tipo di timbro con il nome pasringType. |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Oggetto tipo timbro rotondo.


### Square {#Square}
```
public static final StampType Square
```


Oggetto tipo timbro quadrato.


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Tutti i tipi di timbro.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Restituisce il tipo di timbro con il nome pasringType. Quando il nome del timbro è sconosciuto - viene lanciata un'eccezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | parsingType | java.lang.String | Stringa sorgente del nome del tipo di timbro. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Restituisce il tipo di timbro con il nome pasringType. Quando il nome del timbro è sconosciuto - non viene lanciata alcuna eccezione e il metodo restituisce il valore null.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | parsingType | java.lang.String | Stringa sorgente del nome del tipo di timbro. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

