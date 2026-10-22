---
title: "PdfTextStickerAppearance"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Décrit l'apparence de l'objet autocollant d'annotation de texte PDF et la fenêtre contextuelle de l'autocollant."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

Décrit l'apparence de l'objet autocollant d'annotation de texte PDF et la fenêtre contextuelle de l'autocollant.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | Crée un objet d'apparence d'annotation de texte de signature PDF. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTitle()](#getTitle--) | Obtient ou définit le titre de la fenêtre contextuelle. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Obtient ou définit le titre de la fenêtre contextuelle. |
| [getSubject()](#getSubject--) | Obtient ou définit le sujet. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Obtient ou définit le sujet. |
| [getContents()](#getContents--) | Obtient ou définit le contenu de la fenêtre contextuelle. |
| [setContents(String value)](#setContents-java.lang.String-) | Obtient ou définit le contenu de la fenêtre contextuelle. |
| [getOpened()](#getOpened--) | Définissez si la fenêtre contextuelle de l'autocollant sera ouverte par défaut. |
| [setOpened(boolean value)](#setOpened-boolean-) | Définissez si la fenêtre contextuelle de l'autocollant sera ouverte par défaut. |
| [getIcon()](#getIcon--) | Obtient ou définit l'icône de l'autocollant. |
| [setIcon(int value)](#setIcon-int-) | Obtient ou définit l'icône de l'autocollant. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Obtient l'apparence par défaut de l'autocollant. |
| [resetDefaultAppearance()](#resetDefaultAppearance--) | Efface les valeurs de l'apparence par défaut de l'autocollant. |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


Crée un objet d'apparence d'annotation de texte de signature PDF.

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Obtient ou définit le titre de la fenêtre contextuelle.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Obtient ou définit le titre de la fenêtre contextuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Obtient ou définit le sujet.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Obtient ou définit le sujet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Obtient ou définit le contenu de la fenêtre contextuelle.

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Obtient ou définit le contenu de la fenêtre contextuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Définissez si la fenêtre contextuelle de l'autocollant sera ouverte par défaut.

**Returns:**
booléen
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Définissez si la fenêtre contextuelle de l'autocollant sera ouverte par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Obtient ou définit l'icône de l'autocollant.

**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Obtient ou définit l'icône de l'autocollant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Obtient l'apparence par défaut de l'autocollant. Ces propriétés sont appliquées par défaut si la propriété Options.SignatureAppearance n'est pas spécifiée. Les propriétés peuvent être modifiées par l'utilisateur à tout moment.

**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Efface les valeurs de l'apparence par défaut de l'autocollant.

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.

**Returns:**
java.lang.String -
