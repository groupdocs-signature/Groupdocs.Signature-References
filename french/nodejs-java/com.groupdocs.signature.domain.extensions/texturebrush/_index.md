---
title: "TextureBrush"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente le pinceau de texture."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Représente le pinceau de texture.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextureBrush()](#TextureBrush--) | Initialise une nouvelle instance de la classe TextureBrush avec les valeurs par défaut. |
| [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Initialise une nouvelle instance de la classe TextureBrush avec un fichier image. |
| [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Initialise une nouvelle instance de la classe TextureBrush avec l'option de flux d'image. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | Obtient ou définit le chemin du fichier image de la texture. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Obtient ou définit le chemin du fichier image de la texture. |
| [getImageStream()](#getImageStream--) | Obtient ou définit le flux d'image de la texture. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Obtient ou définit le flux d'image de la texture. |
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Initialise une nouvelle instance de la classe TextureBrush avec les valeurs par défaut.

### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Initialise une nouvelle instance de la classe TextureBrush avec un fichier image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageFilePath | java.lang.String | Chemin du fichier image. |

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Initialise une nouvelle instance de la classe TextureBrush avec l'option de flux d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Flux d'image. |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Obtient ou définit le chemin du fichier image de la texture. Cette propriété n'est utilisée que si ImageStream n'est pas spécifié.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Obtient ou définit le chemin du fichier image de la texture. Cette propriété n'est utilisée que si ImageStream n'est pas spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Obtient ou définit le flux d'image de la texture. Si cette propriété est spécifiée, elle est toujours utilisée à la place de ImageFilePath.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Obtient ou définit le flux d'image de la texture. Si cette propriété est spécifiée, elle est toujours utilisée à la place de ImageFilePath.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.io.InputStream |  |

