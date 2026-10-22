---
title: "StampTypes"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Container für Stempeltypen."
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Container für Stempeltypen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Round](#Round) | Rundes Stempeltyp‑Objekt. |
| [Square](#Square) | Quadratisches Stempeltyp‑Objekt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | Alle Stempeltypen. |
| [parse(String parsingType)](#parse-java.lang.String-) | Gibt den Stempeltyp mit dem Namen pasringType zurück. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | Gibt den Stempeltyp mit dem Namen pasringType zurück. |
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Rundes Stempeltyp‑Objekt.

### Square {#Square}
```
public static final StampType Square
```


Quadratisches Stempeltyp‑Objekt.

### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Alle Stempeltypen.

**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


Gibt den Stempeltyp mit dem Namen pasringType zurück. Wenn der Name des Stempels unbekannt ist - wird eine Ausnahme ausgelöst.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Quellzeichenkette des Stempeltyp‑Namens. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


Gibt den Stempeltyp mit dem Namen pasringType zurück. Wenn der Name des Stempels unbekannt ist - wird keine Ausnahme ausgelöst und die Methode gibt den Nullwert zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Quellzeichenkette des Stempeltyp‑Namens. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
