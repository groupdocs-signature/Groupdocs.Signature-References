---
title: "TextSignOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options de signature Text."
type: docs
weight: 18
url: /fr/nodejs-java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

Représente les options de signature Text.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextSignOptions()](#TextSignOptions--) | Initialise une nouvelle instance de la classe SignTextOptions avec les valeurs par défaut. |
| [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | Initialise une nouvelle instance de la classe SignTextOptions avec du texte. |
## Champs

| Champ | Description |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLeft()](#getLeft--) | Position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété LocationMeasureType). |
| [setLeft(int value)](#setLeft-int-) | Position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété LocationMeasureType). |
| [getTop()](#getTop--) | Position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété LocationMeasureType). |
| [setTop(int value)](#setTop-int-) | Position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété LocationMeasureType). |
| [getWidth()](#getWidth--) | Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété SizeMeasureType). |
| [setWidth(int value)](#setWidth-int-) | Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété SizeMeasureType). |
| [getHeight()](#getHeight--) | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété SizeMeasureType). |
| [setHeight(int value)](#setHeight-int-) | Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété SizeMeasureType). |
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
| [getText()](#getText--) | Obtient ou définit le texte de la signature. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte de la signature. |
| [getFont()](#getFont--) | Obtient ou définit la police de la signature. |
| [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Obtient ou définit la police de la signature. |
| [getForeColor()](#getForeColor--) | Obtient ou définit la couleur de premier plan de la signature. |
| [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Obtient ou définit la couleur de premier plan de la signature. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Obtient ou définit le type d'implémentation de la signature texte. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Obtient ou définit le type d'implémentation de la signature texte. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Alignement horizontal du texte à l'intérieur d'une signature. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Alignement horizontal du texte à l'intérieur d'une signature. |
| [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Alignement vertical du texte à l'intérieur d'une signature. |
| [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Alignement vertical du texte à l'intérieur d'une signature. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Obtient ou définit le titre du champ de formulaire texte dans lequel placer la signature texte. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Obtient ou définit le titre du champ de formulaire texte dans lequel placer la signature texte. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Obtient ou définit le type de champ de formulaire dans lequel placer la signature texte. |
| [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | Obtient ou définit le type de champ de formulaire dans lequel placer la signature texte. |
| [getShapeType()](#getShapeType--) | Obtient ou définit le type de forme pour placer le texte. |
| [setShapeType(int value)](#setShapeType-int-) | Obtient ou définit le type de forme pour placer le texte. |
| [getSignatureID()](#getSignatureID--) | Obtient ou définit l'ID unique de la signature. |
| [setSignatureID(int value)](#setSignatureID-int-) | Obtient ou définit l'ID unique de la signature. |
| [getBorder()](#getBorder--) | Spécifier les paramètres de bordure |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Spécifier les paramètres de bordure |
| [getBackground()](#getBackground--) | Obtient ou définit les paramètres d'arrière-plan de la signature. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Obtient ou définit les paramètres d'arrière-plan de la signature. |
| [getNative()](#getNative--) | Obtient ou définit l'attribut natif. |
| [setNative(boolean value)](#setNative-boolean-) | Obtient ou définit l'attribut natif. |
| [getShapePosition()](#getShapePosition--) | Définit où la forme doit être présentée dans la mise en page du document. |
| [setShapePosition(int value)](#setShapePosition-int-) | Définit où la forme doit être présentée dans la mise en page du document. |
| [validate()](#validate--) | Méthode interne pour valider les paramètres des options. |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


Initialise une nouvelle instance de la classe SignTextOptions avec les valeurs par défaut.

### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


Initialise une nouvelle instance de la classe SignTextOptions avec du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Texte de la signature. |

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


Position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié).

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Position X gauche de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété LocationMeasureType). (fonctionne si l'alignement horizontal n'est pas spécifié).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié).

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Position Y supérieure de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété LocationMeasureType). (fonctionne si l'alignement vertical n'est pas spécifié).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété SizeMeasureType).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Largeur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété SizeMeasureType).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété SizeMeasureType).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hauteur de la signature sur la page du document en valeurs de mesure (pixels, pourcentages ou millimètres, voir [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) propriété SizeMeasureType).

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

### getText() {#getText--}
```
public final String getText()
```


Obtient ou définit le texte de la signature.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Obtient ou définit le texte de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Obtient ou définit la police de la signature.

**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Obtient ou définit la police de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Obtient ou définit la couleur de premier plan de la signature.

**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Obtient ou définit la couleur de premier plan de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Obtient ou définit le type d'implémentation de la signature texte.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Obtient ou définit le type d'implémentation de la signature texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


Alignement horizontal du texte à l'intérieur d'une signature. Cette fonctionnalité n'est prise en charge que pour les implémentations de signature Image et Annotation (voir [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) propriété SignatureImplementation).

**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


Alignement horizontal du texte à l'intérieur d'une signature. Cette fonctionnalité n'est prise en charge que pour les implémentations de signature Image et Annotation (voir [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) propriété SignatureImplementation).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Alignement vertical du texte à l'intérieur d'une signature. Cette fonctionnalité n'est prise en charge que pour l'implémentation de signature Image (voir [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) propriété SignatureImplementation).

**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Alignement vertical du texte à l'intérieur d'une signature. Cette fonctionnalité n'est prise en charge que pour l'implémentation de signature Image (voir [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) propriété SignatureImplementation).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Obtient ou définit le titre du champ de formulaire texte dans lequel placer la signature texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextToFormField.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Obtient ou définit le titre du champ de formulaire texte dans lequel placer la signature texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextToFormField.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


Obtient ou définit le type de champ de formulaire dans lequel placer la signature texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextToFormField. La valeur par défaut est AllTextTypes.

**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


Obtient ou définit le type de champ de formulaire dans lequel placer la signature texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextToFormField. La valeur par défaut est AllTextTypes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Obtient ou définit le type de forme pour placer le texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextStamp. La valeur par défaut est Rectangle.

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


Obtient ou définit le type de forme pour placer le texte. Cette propriété ne peut être utilisée qu'avec SignatureImplementation = TextStamp. La valeur par défaut est Rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Obtient ou définit l'ID unique de la signature. Il peut être utilisé dans les options de vérification de signature. La propriété n'est prise en charge que pour les documents PDF.

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Obtient ou définit l'ID unique de la signature. Il peut être utilisé dans les options de vérification de signature. La propriété n'est prise en charge que pour les documents PDF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Obtient ou définit les paramètres d'arrière-plan de la signature.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Obtient ou définit les paramètres d'arrière-plan de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


Obtient ou définit l'attribut natif. S'il est défini, des signatures spécifiques au document peuvent être utilisées. Le filigrane texte natif pour les documents de traitement de texte est différent du filigrane ordinaire, par exemple.

**Returns:**
booléen
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Obtient ou définit l'attribut natif. S'il est défini, des signatures spécifiques au document peuvent être utilisées. Le filigrane texte natif pour les documents de traitement de texte est différent du filigrane ordinaire, par exemple.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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

### validate() {#validate--}
```
public void validate()
```


Méthode interne pour valider les paramètres des options.

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.

**Returns:**
java.lang.String -
