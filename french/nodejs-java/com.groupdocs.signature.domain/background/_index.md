---
title: "Arrière-plan"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente l'apparence d'arrière-plan"
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Représente l'apparence d'arrière-plan
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Background()](#Background--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor()](#getColor--) | Obtient ou définit la couleur d'arrière-plan de la signature. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Obtient ou définit la couleur d'arrière-plan de la signature. |
| [setColor(String value)](#setColor-java.lang.String-) | Obtient ou définit la couleur d'arrière-plan de la signature. |
| [getTransparency()](#getTransparency--) | Obtient ou définit la transparence de l'arrière-plan (valeur de 0,0 (opaque) à 1,0 (transparent)). |
| [setTransparency(double value)](#setTransparency-double-) | Obtient ou définit la transparence de l'arrière-plan (valeur de 0,0 (opaque) à 1,0 (transparent)). |
| [getBrush()](#getBrush--) | Obtient ou définit le pinceau d'arrière-plan. |
| [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Obtient ou définit le pinceau d'arrière-plan. |
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


Obtient ou définit la couleur d'arrière-plan de la signature.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Obtient ou définit la couleur d'arrière-plan de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Obtient ou définit la couleur d'arrière-plan de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Obtient ou définit la transparence de l'arrière-plan (valeur de 0,0 (opaque) à 1,0 (transparent)).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Obtient ou définit la transparence de l'arrière-plan (valeur de 0,0 (opaque) à 1,0 (transparent)).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Obtient ou définit le pinceau d'arrière-plan. La valeur par défaut est null. Cette propriété attend une instance d'implémentations d'objets Brush. Voir les différentes classes Brush.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Obtient ou définit le pinceau d'arrière-plan. La valeur par défaut est null. Cette propriété attend une instance d'implémentations d'objets Brush. Voir les différentes classes Brush.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

