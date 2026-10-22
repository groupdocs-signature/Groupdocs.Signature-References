---
title: "Coins"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les coins d'un objet graphique carré."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Représente les coins d'un objet graphique carré.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Corners()](#Corners--) | Initialise une nouvelle instance de la classe Corners en utilisant des valeurs zéro. |
| [Corners(double all)](#Corners-double-) | Initialise une nouvelle instance de la classe Corners en utilisant la valeur fournie pour tous les coins. |
| [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Initialise une nouvelle instance de la classe Corners en utilisant les valeurs fournies. |
## Champs

| Champ | Description |
| --- | --- |
| [Empty](#Empty) | Fournit un objet Corners sans données. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAll()](#getAll--) | Obtient ou définit la valeur pour tous les coins. |
| [setAll(double value)](#setAll-double-) | Obtient ou définit la valeur pour tous les coins. |
| [getTopLeft()](#getTopLeft--) | Obtient ou définit la valeur du coin supérieur gauche. |
| [setTopLeft(double value)](#setTopLeft-double-) | Obtient ou définit la valeur du coin supérieur gauche. |
| [getTopRight()](#getTopRight--) | Obtient ou définit la valeur du coin supérieur droit. |
| [setTopRight(double value)](#setTopRight-double-) | Obtient ou définit la valeur du coin supérieur droit. |
| [getBottomLeft()](#getBottomLeft--) | Obtient ou définit la valeur du coin inférieur gauche. |
| [setBottomLeft(double value)](#setBottomLeft-double-) | Obtient ou définit la valeur du coin inférieur gauche. |
| [getBottomRight()](#getBottomRight--) | Obtient ou définit la valeur du coin inférieur droit. |
| [setBottomRight(double value)](#setBottomRight-double-) | Obtient ou définit la valeur du coin inférieur droit. |
| [deepClone()](#deepClone--) | Obtient une copie de cet objet. |
| [equals(Object obj)](#equals-java.lang.Object-) | Remplace la méthode equals |
| [hashCode()](#hashCode--) | Surcharge l'obtention d'une valeur de code de hachage unique |
| [toString()](#toString--) | Surcharge la conversion en chaîne. |
### Corners() {#Corners--}
```
public Corners()
```


Initialise une nouvelle instance de la classe Corners en utilisant des valeurs zéro.

### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Initialise une nouvelle instance de la classe Corners en utilisant la valeur fournie pour tous les coins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tout | double | La valeur à utiliser pour le remplissage de tous les coins. |

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Initialise une nouvelle instance de la classe Corners en utilisant les valeurs fournies.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| topLeft | double | Valeur du coin supérieur gauche. |
| topRight | double | Valeur du coin supérieur droit. |
| bottomLeft | double | Valeur du coin inférieur gauche. |
| bottomRight | double | Valeur du coin inférieur droit. |

### Empty {#Empty}
```
public static final Corners Empty
```


Fournit un objet Corners sans données.

### getAll() {#getAll--}
```
public final double getAll()
```


Obtient ou définit la valeur pour tous les coins. Modifier un coin partiel comme le coin supérieur droit rend cette propriété égale à 0;

**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Obtient ou définit la valeur pour tous les coins. Modifier un coin partiel comme le coin supérieur droit rend cette propriété égale à 0;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Obtient ou définit la valeur du coin supérieur gauche.

**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Obtient ou définit la valeur du coin supérieur gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Obtient ou définit la valeur du coin supérieur droit.

**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Obtient ou définit la valeur du coin supérieur droit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Obtient ou définit la valeur du coin inférieur gauche.

**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Obtient ou définit la valeur du coin inférieur gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Obtient ou définit la valeur du coin inférieur droit.

**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Obtient ou définit la valeur du coin inférieur droit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Obtient une copie de cet objet.

**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Remplace la méthode equals

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Instance à comparer avec. |

**Returns:**
boolean - Retourne true si les propriétés des objets sont égales.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Surcharge l'obtention d'une valeur de code de hachage unique

**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Surcharge la conversion en chaîne.

**Returns:**
java.lang.String -
