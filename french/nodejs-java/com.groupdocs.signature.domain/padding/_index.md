---
title: "Marge"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les informations de remplissage ou de marge associées à l'élément."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Représente les informations de remplissage ou de marge associées à l'élément.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Padding()](#Padding--) | Initialise une nouvelle instance de la classe Padding en utilisant des valeurs zéro. |
| [Padding(int all)](#Padding-int-) | Initialise une nouvelle instance de la classe Padding en utilisant la taille de marge fournie pour tous les côtés. |
| [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Initialise une nouvelle instance de la classe Padding en utilisant les tailles de marge fournies. |
## Champs

| Champ | Description |
| --- | --- |
| [Empty](#Empty) | Fournit un objet Padding sans marge. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAll()](#getAll--) | Obtient ou définit la valeur de marge pour tous les côtés. |
| [setAll(int value)](#setAll-int-) | Obtient ou définit la valeur de marge pour tous les côtés. |
| [getLeft()](#getLeft--) | Obtient ou définit la valeur de marge pour le côté gauche. |
| [setLeft(int value)](#setLeft-int-) | Obtient ou définit la valeur de marge pour le côté gauche. |
| [getRight()](#getRight--) | Obtient ou définit la valeur de marge pour le côté droit. |
| [setRight(int value)](#setRight-int-) | Obtient ou définit la valeur de marge pour le côté droit. |
| [getTop()](#getTop--) | Obtient ou définit la valeur de marge pour le côté supérieur. |
| [setTop(int value)](#setTop-int-) | Obtient ou définit la valeur de marge pour le côté supérieur. |
| [getBottom()](#getBottom--) | Obtient ou définit la valeur de marge pour le côté inférieur. |
| [setBottom(int value)](#setBottom-int-) | Obtient ou définit la valeur de marge pour le côté inférieur. |
| [getHorizontal()](#getHorizontal--) | Obtient la marge combinée pour les côtés droit et gauche. |
| [getVertical()](#getVertical--) | Obtient la marge combinée pour les côtés supérieur et inférieur. |
| [deepClone()](#deepClone--) | Obtient une copie de cet objet. |
| [toString()](#toString--) | Remplace la conversion en chaîne |
### Padding() {#Padding--}
```
public Padding()
```


Initialise une nouvelle instance de la classe Padding en utilisant des valeurs zéro.

### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Initialise une nouvelle instance de la classe Padding en utilisant la taille de marge fournie pour tous les côtés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tout | int | Le nombre d'unités de mesure à utiliser pour la marge sur tous les côtés. |

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Initialise une nouvelle instance de la classe Padding en utilisant les tailles de marge fournies.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | int | La taille de la marge gauche. |
| droite | int | La taille du remplissage à droite. |
| haut | int | La taille du remplissage en haut. |
| bas | int | La taille du remplissage en bas. |

### Empty {#Empty}
```
public static final Padding Empty
```


Fournit un objet Padding sans marge.

### getAll() {#getAll--}
```
public final int getAll()
```


Obtient ou définit la valeur du remplissage pour tous les bords. Modifier un bord partiel comme la gauche ou le haut rend cette propriété égale à 0;

**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Obtient ou définit la valeur du remplissage pour tous les bords. Modifier un bord partiel comme la gauche ou le haut rend cette propriété égale à 0;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Obtient ou définit la valeur de marge pour le côté gauche.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Obtient ou définit la valeur de marge pour le côté gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Obtient ou définit la valeur de marge pour le côté droit.

**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Obtient ou définit la valeur de marge pour le côté droit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Obtient ou définit la valeur de marge pour le côté supérieur.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Obtient ou définit la valeur de marge pour le côté supérieur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Obtient ou définit la valeur de marge pour le côté inférieur.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Obtient ou définit la valeur de marge pour le côté inférieur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Obtient la marge combinée pour les côtés droit et gauche.

**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Obtient la marge combinée pour les côtés supérieur et inférieur.

**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Obtient une copie de cet objet.

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Remplace la conversion en chaîne

**Returns:**
java.lang.String -
