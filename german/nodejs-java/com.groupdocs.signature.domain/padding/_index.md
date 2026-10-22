---
title: "Abstand"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt Polster‑ oder Randinformationen dar, die mit dem Element verknüpft sind."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Stellt Polster‑ oder Randinformationen dar, die mit dem Element verknüpft sind.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Padding()](#Padding--) | Initialisiert eine neue Instanz der Padding-Klasse mit Nullwerten. |
| [Padding(int all)](#Padding-int-) | Initialisiert eine neue Instanz der Padding-Klasse mit der angegebenen Abstandgröße für alle Kanten. |
| [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Initialisiert eine neue Instanz der Padding-Klasse mit den angegebenen Abstandgrößen. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Empty](#Empty) | Stellt ein Padding-Objekt ohne Abstand bereit. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAll()](#getAll--) | Liest oder setzt den Abstandswert für alle Kanten. |
| [setAll(int value)](#setAll-int-) | Liest oder setzt den Abstandswert für alle Kanten. |
| [getLeft()](#getLeft--) | Liest oder setzt den Abstandswert für die linke Kante. |
| [setLeft(int value)](#setLeft-int-) | Liest oder setzt den Abstandswert für die linke Kante. |
| [getRight()](#getRight--) | Liest oder setzt den Abstandswert für die rechte Kante. |
| [setRight(int value)](#setRight-int-) | Liest oder setzt den Abstandswert für die rechte Kante. |
| [getTop()](#getTop--) | Liest oder setzt den Abstandswert für die obere Kante. |
| [setTop(int value)](#setTop-int-) | Liest oder setzt den Abstandswert für die obere Kante. |
| [getBottom()](#getBottom--) | Liest oder setzt den Abstandswert für die untere Kante. |
| [setBottom(int value)](#setBottom-int-) | Liest oder setzt den Abstandswert für die untere Kante. |
| [getHorizontal()](#getHorizontal--) | Liest den kombinierten Abstand für die rechte und linke Kante. |
| [getVertical()](#getVertical--) | Liest den kombinierten Abstand für die obere und untere Kante. |
| [deepClone()](#deepClone--) | Liefert eine Kopie dieses Objekts. |
| [toString()](#toString--) | Überschreibt die Konvertierung in einen String |
### Padding() {#Padding--}
```
public Padding()
```


Initialisiert eine neue Instanz der Padding-Klasse mit Nullwerten.

### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Initialisiert eine neue Instanz der Padding-Klasse mit der angegebenen Abstandgröße für alle Kanten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alle | int | Die Anzahl der Maßeinheiten, die für das Padding aller Kanten verwendet werden soll. |

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Initialisiert eine neue Instanz der Padding-Klasse mit den angegebenen Abstandgrößen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | int | Die Größe des linken Paddings. |
| rechts | int | Die Größe des rechten Paddings. |
| oben | int | Die Größe des oberen Paddings. |
| unten | int | Die Größe des unteren Paddings. |

### Empty {#Empty}
```
public static final Padding Empty
```


Stellt ein Padding-Objekt ohne Abstand bereit.

### getAll() {#getAll--}
```
public final int getAll()
```


Liest oder setzt den Padding-Wert für alle Kanten. Das Ändern einer beliebigen Teilkante wie links oder oben setzt diese Eigenschaft auf 0;

**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Liest oder setzt den Padding-Wert für alle Kanten. Das Ändern einer beliebigen Teilkante wie links oder oben setzt diese Eigenschaft auf 0;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Liest oder setzt den Abstandswert für die linke Kante.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Liest oder setzt den Abstandswert für die linke Kante.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Liest oder setzt den Abstandswert für die rechte Kante.

**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Liest oder setzt den Abstandswert für die rechte Kante.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Liest oder setzt den Abstandswert für die obere Kante.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Liest oder setzt den Abstandswert für die obere Kante.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Liest oder setzt den Abstandswert für die untere Kante.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Liest oder setzt den Abstandswert für die untere Kante.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Liest den kombinierten Abstand für die rechte und linke Kante.

**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Liest den kombinierten Abstand für die obere und untere Kante.

**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Liefert eine Kopie dieses Objekts.

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Überschreibt die Konvertierung in einen String

**Returns:**
java.lang.String -
