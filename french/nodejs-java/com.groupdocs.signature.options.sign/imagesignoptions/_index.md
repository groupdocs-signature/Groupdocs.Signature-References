---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options de signature Image."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Représente les options de signature Image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageSignOptions()](#ImageSignOptions--) | Initialise une nouvelle instance de la classe ImageSignOptions avec les valeurs par défaut. |
| [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Initialise une nouvelle instance de la classe ImageSignOptions avec un fichier image. |
| [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Initialise une nouvelle instance de la classe ImageSignOptions avec un flux d'image. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | Obtient ou définit le chemin du fichier d'image de signature. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Obtient ou définit le chemin du fichier d'image de signature. |
| [getImageStream()](#getImageStream--) | Obtient ou définit le flux d'image de signature. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Obtient ou définit le flux d'image de signature. |
| [getLeft()](#getLeft--) | Position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setLeft(int value)](#setLeft-int-) | Position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getTop()](#getTop--) | Position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [setTop(int value)](#setTop-int-) | Position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). |
| [getWidth()](#getWidth--) | Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setWidth(int value)](#setWidth-int-) | Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [getHeight()](#getHeight--) | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [setHeight(int value)](#setHeight-int-) | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType). |
| [getLocationMeasureType()](#getLocationMeasureType--) | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Left et Top. |
| [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Left et Top. |
| [getSizeMeasureType()](#getSizeMeasureType--) | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height. |
| [getStretch()](#getStretch--) | Mode d'étirement sur la page du document. |
| [setStretch(int value)](#setStretch-int-) | Mode d'étirement sur la page du document. |
| [getRotationAngle()](#getRotationAngle--) | Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre). |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Alignement horizontal de la signature sur la page du document. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Alignement horizontal de la signature sur la page du document. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Alignement vertical de la signature sur la page du document. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Alignement vertical de la signature sur la page du document. |
| [getMargin()](#getMargin--) | Obtient ou définit l'espace entre la signature et les bords du document. |
| [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Obtient ou définit l'espace entre la signature et les bords du document. |
| [getMarginMeasureType()](#getMarginMeasureType--) | Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour la marge. |
| [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour la marge. |
| [getTransparency()](#getTransparency--) | Obtient ou définit la transparence de la signature (valeur de 0,0 (opaque) à 1,0 (transparent)). |
| [setTransparency(double value)](#setTransparency-double-) | Obtient ou définit la transparence de la signature (valeur de 0,0 (opaque) à 1,0 (transparent)). |
| [getShapePosition()](#getShapePosition--) | Définit où la forme doit être présentée dans la mise en page du document. |
| [setShapePosition(int value)](#setShapePosition-int-) | Définit où la forme doit être présentée dans la mise en page du document. |
| [getRectangle()](#getRectangle--) | Rectangle de la zone où placer l'image sur le document. |
| [getBorder()](#getBorder--) | Spécifier les paramètres de bordure |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Spécifier les paramètres de bordure |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
| [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Crée une nouvelle instance de la classe ImageSignOptions avec une image prédéfinie à partir de Base64. |
| [dispose()](#dispose--) | Efface les ressources internes |
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Initialise une nouvelle instance de la classe ImageSignOptions avec les valeurs par défaut.

### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Initialise une nouvelle instance de la classe ImageSignOptions avec un fichier image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageFilePath | java.lang.String | Chemin du fichier image |

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Initialise une nouvelle instance de la classe ImageSignOptions avec un flux d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Flux d'image |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Obtient ou définit le chemin du fichier image de la signature. Cette propriété n'est utilisée que si ImageStream n'est pas spécifié.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Obtient ou définit le chemin du fichier image de la signature. Cette propriété n'est utilisée que si ImageStream n'est pas spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Obtient ou définit le flux d'image de la signature. Si cette propriété est spécifiée, elle est toujours utilisée à la place de ImageGuid.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Obtient ou définit le flux d'image de la signature. Si cette propriété est spécifiée, elle est toujours utilisée à la place de ImageGuid.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Left et Top.

**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Left et Top.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height.

**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Type de mesure (pixels, pourcentages ou millimètres) pour les propriétés Width et Height.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Mode d'étirement sur la page du document.

**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Mode d'étirement sur la page du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre).

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Angle de rotation de la signature sur la page du document (dans le sens des aiguilles d'une montre).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Alignement horizontal de la signature sur la page du document.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Alignement horizontal de la signature sur la page du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Alignement vertical de la signature sur la page du document.

**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Alignement vertical de la signature sur la page du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Obtient ou définit l'espace entre la signature et les bords du document. (fonctionne UNIQUEMENT si l'alignement horizontal ou vertical est spécifié).

**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Obtient ou définit l'espace entre la signature et les bords du document. (fonctionne UNIQUEMENT si l'alignement horizontal ou vertical est spécifié).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour la marge.

**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Obtient ou définit le type de mesure (pixels, pourcentages ou millimètres) pour la marge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Obtient ou définit la transparence de la signature (valeur de 0,0 (opaque) à 1,0 (transparent)). La valeur par défaut est 0 (opaque).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Obtient ou définit la transparence de la signature (valeur de 0,0 (opaque) à 1,0 (transparent)). La valeur par défaut est 0 (opaque).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Définit où la forme doit être présentée dans la mise en page du document.

**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Définit où la forme doit être présentée dans la mise en page du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Rectangle de la zone où placer l'image sur le document.

**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Spécifier les paramètres de bordure

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Spécifier les paramètres de bordure

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.

**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Crée une nouvelle instance de la classe ImageSignOptions avec une image prédéfinie à partir de Base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| base64Content | java.lang.String | Contenu de l'image au format chaîne Base64 |

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Efface les ressources internes

