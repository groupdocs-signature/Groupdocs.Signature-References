---
title: "Padding"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les informations de remplissage ou de marge associées à l'élément."
type: docs
weight: 13
url: /fr/java/com.groupdocs.signature.domain/padding/
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
|  | [Padding()](#Padding--) | Initialise une nouvelle instance de la classe Padding en utilisant des valeurs zéro. |
|
|  | [Padding(int all)](#Padding-int-) | Initialise une nouvelle instance de la classe Padding en utilisant la taille de remplissage fournie pour tous les bords. |
|
|  | [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Initialise une nouvelle instance de la classe Padding en utilisant les tailles de remplissage fournies. |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Empty](#Empty) | Fournit un objet Padding sans remplissage. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAll()](#getAll--) | Obtient ou définit la valeur de remplissage pour tous les bords. |
|
|  | [setAll(int value)](#setAll-int-) | Obtient ou définit la valeur de remplissage pour tous les bords. |
|
|  | [getLeft()](#getLeft--) | Obtient ou définit la valeur de remplissage pour le bord gauche. |
|
|  | [setLeft(int value)](#setLeft-int-) | Obtient ou définit la valeur de remplissage pour le bord gauche. |
|
|  | [getRight()](#getRight--) | Obtient ou définit la valeur de remplissage pour le bord droit. |
|
|  | [setRight(int value)](#setRight-int-) | Obtient ou définit la valeur de remplissage pour le bord droit. |
|
|  | [getTop()](#getTop--) | Obtient ou définit la valeur de remplissage pour le bord supérieur. |
|
|  | [setTop(int value)](#setTop-int-) | Obtient ou définit la valeur de remplissage pour le bord supérieur. |
|
|  | [getBottom()](#getBottom--) | Obtient ou définit la valeur de remplissage pour le bord inférieur. |
|
|  | [setBottom(int value)](#setBottom-int-) | Obtient ou définit la valeur de remplissage pour le bord inférieur. |
|
|  | [getHorizontal()](#getHorizontal--) | Obtient le remplissage combiné pour les bords droit et gauche. |
|
|  | [getVertical()](#getVertical--) | Obtient le remplissage combiné pour les bords supérieur et inférieur. |
|
|  | [deepClone()](#deepClone--) | Obtient une copie de cet objet. |
|
|  | [toString()](#toString--) | Remplace la conversion en chaîne |
|
### Padding() {#Padding--}
```
public Padding()
```


Initialise une nouvelle instance de la classe Padding en utilisant des valeurs zéro.


### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Initialise une nouvelle instance de la classe Padding en utilisant la taille de remplissage fournie pour tous les bords.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | tout | int | Le nombre d'unités de mesure à utiliser pour le remplissage de tous les bords. |
|

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Initialise une nouvelle instance de la classe Padding en utilisant les tailles de remplissage fournies.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | gauche | int | La taille du remplissage gauche. |
|
|  | droite | int | La taille du remplissage à droite. |
|
|  | haut | int | La taille du remplissage supérieur. |
|
|  | bas | int | La taille du remplissage inférieur. |
|

### Empty {#Empty}
```
public static final Padding Empty
```


Fournit un objet Padding sans remplissage.


### getAll() {#getAll--}
```
public final int getAll()
```


Obtient ou définit la valeur de remplissage pour tous les bords.
Modifier n'importe quel bord partiel comme la gauche ou le haut rend cette propriété égale à 0;


**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Obtient ou définit la valeur de remplissage pour tous les bords.
Modifier n'importe quel bord partiel comme la gauche ou le haut rend cette propriété égale à 0;


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Obtient ou définit la valeur de remplissage pour le bord gauche.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Obtient ou définit la valeur de remplissage pour le bord gauche.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Obtient ou définit la valeur de remplissage pour le bord droit.


**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Obtient ou définit la valeur de remplissage pour le bord droit.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Obtient ou définit la valeur de remplissage pour le bord supérieur.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Obtient ou définit la valeur de remplissage pour le bord supérieur.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Obtient ou définit la valeur de remplissage pour le bord inférieur.


**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Obtient ou définit la valeur de remplissage pour le bord inférieur.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Obtient le remplissage combiné pour les bords droit et gauche.


**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Obtient le remplissage combiné pour les bords supérieur et inférieur.


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
