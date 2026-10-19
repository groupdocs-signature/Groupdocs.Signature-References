---
title: "Bordure"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Instance pour conserver les propriétés de la ligne de bordure."
type: docs
weight: 11
url: /fr/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Instance pour conserver les propriétés de la ligne de bordure.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Border()](#Border--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | Obtient ou définit le style de bordure de la signature. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Obtient ou définit le style de bordure de la signature. |
|
|  | [getTransparency()](#getTransparency--) | Obtient ou définit la transparence de la bordure de la signature (valeur de 0.0 (opaque) à 1.0 (transparent)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Obtient ou définit la transparence de la bordure de la signature (valeur de 0.0 (opaque) à 1.0 (transparent)). |
|
|  | [getWeight()](#getWeight--) | Obtient ou définit l'épaisseur de la bordure de la signature. |
|
|  | [setWeight(double value)](#setWeight-double-) | Obtient ou définit l'épaisseur de la bordure de la signature. |
|
|  | [getColor()](#getColor--) | Obtient ou définit la couleur de la bordure de la signature. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Obtient ou définit la couleur de la bordure de la signature. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Obtient ou définit la couleur de la bordure de la signature. |
|
|  | [getVisible()](#getVisible--) | Obtient ou définit la visibilité de la bordure. |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | Implémente l'interface IClonable |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Obtient ou définit le style de bordure de la signature.


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Obtient ou définit le style de bordure de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Obtient ou définit la transparence de la bordure de la signature (valeur de 0.0 (opaque) à 1.0 (transparent)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Obtient ou définit la transparence de la bordure de la signature (valeur de 0.0 (opaque) à 1.0 (transparent)).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Obtient ou définit l'épaisseur de la bordure de la signature.


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Obtient ou définit l'épaisseur de la bordure de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Obtient ou définit la couleur de la bordure de la signature.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Obtient ou définit la couleur de la bordure de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Obtient ou définit la couleur de la bordure de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Obtient ou définit la visibilité de la bordure.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Implémente l'interface IClonable


**Returns:**
java.lang.Object - Nouvelle instance de Border créée avec les mêmes propriétés

