---
title: "TextShadow"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les propriétés d'ombre du texte pour les signatures de texte."
type: docs
weight: 13
url: /fr/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Représente les propriétés d'ombre du texte pour les signatures de texte.
Le résultat peut varier en fonction du type de signature et du format du document.
TextShadow est recommandé pour une utilisation avec la signature TextAsImage pour tous les types de documents pris en charge,
également avec une simple TextSignature et TextSignature en tant que filigrane pour Cells (.xslx) et Slides (.pptx).
Une TextSignature simple pour Words (.docx) est également recommandée, mais possède des fonctionnalités limitées.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | Crée un TextShadow avec les options par défaut. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getDistance()](#getDistance--) | Obtient ou définit la distance du texte à l'ombre. |
|
|  | [setDistance(double value)](#setDistance-double-) | Obtient ou définit la distance du texte à l'ombre. |
|
|  | [getAngle()](#getAngle--) | Obtient ou définit l'angle de placement de l'ombre par rapport au texte. |
|
|  | [setAngle(double value)](#setAngle-double-) | Obtient ou définit l'angle de placement de l'ombre par rapport au texte. |
|
|  | [getColor()](#getColor--) | Obtient ou définit la couleur de l'ombre. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Obtient ou définit la couleur de l'ombre. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Obtient ou définit la couleur de l'ombre. |
|
|  | [getTransparency()](#getTransparency--) | Obtient ou définit la transparence de l'ombre. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Obtient ou définit la transparence de l'ombre. |
|
|  | [getBlur()](#getBlur--) | Obtient ou définit le flou de l'ombre. |
|
|  | [setBlur(double value)](#setBlur-double-) | Obtient ou définit le flou de l'ombre. |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Crée un TextShadow avec les options par défaut.


### getDistance() {#getDistance--}
```
public final double getDistance()
```


Obtient ou définit la distance du texte à l'ombre.
La valeur par défaut est 1.


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Obtient ou définit la distance du texte à l'ombre.
La valeur par défaut est 1.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Obtient ou définit l'angle de placement de l'ombre par rapport au texte.
La valeur par défaut est 0.


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Obtient ou définit l'angle de placement de l'ombre par rapport au texte.
La valeur par défaut est 0.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Obtient ou définit la couleur de l'ombre.
La valeur par défaut est Noir.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Obtient ou définit la couleur de l'ombre.
La valeur par défaut est Noir.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Obtient ou définit la couleur de l'ombre.
La valeur par défaut est Noir.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Obtient ou définit la transparence de l'ombre.
La valeur par défaut est 0.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Obtient ou définit la transparence de l'ombre.
La valeur par défaut est 0.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Obtient ou définit le flou de l'ombre.
La valeur par défaut est 4.


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Obtient ou définit le flou de l'ombre.
La valeur par défaut est 4.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

