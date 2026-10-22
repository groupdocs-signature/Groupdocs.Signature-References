---
title: "StampTypes"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contenitore dei tipi di timbro."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.signature.domain.stamps/stamptypes/
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
| [Round](#Round) | Oggetto di tipo stamp rotondo. |
| [Square](#Square) | Oggetto di tipo stamp quadrato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | Tutti i tipi di stamp. |
| [parse(String parsingType)](#parse-java.lang.String-) | Restituisce il tipo di stamp con il nome pasringType. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | Restituisce il tipo di stamp con il nome pasringType. |
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Oggetto di tipo stamp rotondo.

### Square {#Square}
```
public static final StampType Square
```


Oggetto di tipo stamp quadrato.

### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Tutti i tipi di stamp.

**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Restituisce il tipo di stamp con il nome pasringType. Quando il nome del stamp è sconosciuto - viene lanciata un'eccezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Stringa sorgente del nome del tipo di stamp. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Restituisce il tipo di stamp con il nome pasringType. Quando il nome del stamp è sconosciuto - non viene lanciata alcuna eccezione e il metodo restituisce il valore null.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Stringa sorgente del nome del tipo di stamp. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
