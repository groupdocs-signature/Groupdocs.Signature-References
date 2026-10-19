---
title: "StampSignOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options de signature de tampon."
type: docs
weight: 17
url: /fr/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Représente les options de signature de tampon.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | Initialise une nouvelle instance de la classe StampSignOptions avec les valeurs par défaut. |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Initialise une nouvelle instance de la classe StampSignOptions avec des options d'alignement. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getStampType()](#getStampType--) | Obtient ou définit le type de tampon. |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Obtient ou définit le type de tampon. |
|
|  | [getOuterLines()](#getOuterLines--) | Liste des lignes extérieures rendues sous forme de cercles concentriques. |
|
|  | [getInnerLines()](#getInnerLines--) | Liste des lignes intérieures rendues sous forme d'ensemble de rectangles. |
|
|  | [getBackground()](#getBackground--) | Obtient ou définit l'arrière-plan du tampon. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Obtient ou définit l'arrière-plan du tampon. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Obtient ou définit la couleur d'arrière-plan de la signature. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Obtient ou définit la couleur d'arrière-plan de la signature. |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | Obtient ou définit le pinceau d'arrière-plan de la signature. |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Obtient ou définit le pinceau d'arrière-plan de la signature. |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Obtient ou définit le type de recadrage de couleur d'arrière-plan de la signature. |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Obtient ou définit le type de recadrage de couleur d'arrière-plan de la signature. |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Obtient ou définit le type de recadrage d'image d'arrière-plan de la signature. |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Obtient ou définit le type de recadrage d'image d'arrière-plan de la signature. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Initialise une nouvelle instance de la classe StampSignOptions avec les valeurs par défaut.


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Initialise une nouvelle instance de la classe StampSignOptions avec des options d'alignement.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | gauche | int | La coordonnée x du bord supérieur gauche de la signature du tampon |
|
|  | haut | int | La coordonnée y du bord supérieur gauche de la signature du tampon |
|
|  | largeur | int | La largeur de la signature du tampon |
|
|  | hauteur | int | La hauteur de la signature du tampon |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Obtient ou définit le type de tampon.
La valeur par défaut est Round.


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Obtient ou définit le type de tampon.
La valeur par défaut est Round.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Liste des lignes extérieures rendues sous forme de cercles concentriques.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


Liste des lignes intérieures rendues sous forme d'ensemble de rectangles.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Obtient ou définit l'arrière-plan du tampon.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Obtient ou définit l'arrière-plan du tampon.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Obtient ou définit la couleur d'arrière-plan de la signature.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Obtient ou définit la couleur d'arrière-plan de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Obtient ou définit le pinceau d'arrière-plan de la signature. La valeur par défaut est null.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Obtient ou définit le pinceau d'arrière-plan de la signature. La valeur par défaut est null.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Obtient ou définit le type de recadrage de couleur d'arrière-plan de la signature.


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Obtient ou définit le type de recadrage de couleur d'arrière-plan de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Obtient ou définit le type de recadrage d'image d'arrière-plan de la signature.


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Obtient ou définit le type de recadrage d'image d'arrière-plan de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne


**Returns:**
java.lang.String -
