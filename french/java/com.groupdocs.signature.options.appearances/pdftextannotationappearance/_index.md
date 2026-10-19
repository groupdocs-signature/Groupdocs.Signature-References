---
title: "PdfTextAnnotationAppearance"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Décrit l'apparence de l'objet d'annotation de texte PDF Title Subject Content."
type: docs
weight: 13
url: /fr/java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Décrit l'apparence de l'objet d'annotation de texte PDF (Titre, Sujet, Contenu).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Crée l'objet d'apparence d'annotation txt de signature PDF. |
|
|  | [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Crée une annotation txt de signature PDF avec les valeurs spécifiées (title, subject, contents). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getContents()](#getContents--) | Obtient ou définit le contenu de l'objet d'annotation. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Obtient ou définit le contenu de l'objet d'annotation. |
|
|  | [getSubject()](#getSubject--) | Obtient ou définit Subject représentant la description de l'objet. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Obtient ou définit Subject représentant la description de l'objet. |
|
|  | [getTitle()](#getTitle--) | Obtient ou définit un Title qui sera affiché dans la barre de titre de l'objet d'annotation. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Obtient ou définit un Title qui sera affiché dans la barre de titre de l'objet d'annotation. |
|
|  | [getBorder()](#getBorder--) | Obtient ou définit différents paramètres de bordure |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Obtient ou définit différents paramètres de bordure |
|
|  | [getBorderEffect()](#getBorderEffect--) | Obtient ou définit l'effet de bordure. |
|
|  | [setBorderEffect(int value)](#setBorderEffect-int-) | Obtient ou définit l'effet de bordure. |
|
|  | [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Obtient ou définit l'intensité de l'effet de bordure. |
|
|  | [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Obtient ou définit l'intensité de l'effet de bordure. |
|
|  | [getHCornerRadius()](#getHCornerRadius--) | Obtient ou définit le rayon du coin horizontal. |
|
|  | [setHCornerRadius(int value)](#setHCornerRadius-int-) | Obtient ou définit le rayon du coin horizontal. |
|
|  | [getVCornerRadius()](#getVCornerRadius--) | Obtient ou définit le rayon du coin vertical. |
|
|  | [setVCornerRadius(int value)](#setVCornerRadius-int-) | Obtient ou définit le rayon du coin vertical. |
|
|  | [toString()](#toString--) | Remplace la conversion de chaîne. |
|
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Crée l'objet d'apparence d'annotation txt de signature PDF.


### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Crée une annotation txt de signature PDF avec les valeurs spécifiées (title, subject, contents).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | titre | java.lang.String | Titre. |
|
|  | sujet | java.lang.String | Sujet. |
|
|  | contenu | java.lang.String | Contenu. |
|

### getContents() {#getContents--}
```
public final String getContents()
```


Obtient ou définit le contenu de l'objet d'annotation.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Obtient ou définit le contenu de l'objet d'annotation.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Obtient ou définit Subject représentant la description de l'objet.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Obtient ou définit Subject représentant la description de l'objet.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Obtient ou définit un Title qui sera affiché dans la barre de titre de l'objet d'annotation.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Obtient ou définit un Title qui sera affiché dans la barre de titre de l'objet d'annotation.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Obtient ou définit différents paramètres de bordure


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Obtient ou définit différents paramètres de bordure


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Obtient ou définit l'effet de bordure.


**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Obtient ou définit l'effet de bordure.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Obtient ou définit l'intensité de l'effet de bordure. La plage valide de la valeur est [0..2].


**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Obtient ou définit l'intensité de l'effet de bordure. La plage valide de la valeur est [0..2].


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Obtient ou définit le rayon du coin horizontal.


**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Obtient ou définit le rayon du coin horizontal.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Obtient ou définit le rayon du coin vertical.


**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Obtient ou définit le rayon du coin vertical.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.


**Returns:**
java.lang.String -
