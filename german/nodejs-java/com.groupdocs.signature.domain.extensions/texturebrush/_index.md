---
title: "TextureBrush"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt einen Texturpinsel dar."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Stellt einen Texturpinsel dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextureBrush()](#TextureBrush--) | Initialisiert eine neue Instanz der TextureBrush-Klasse mit Standardwerten. |
| [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Initialisiert eine neue Instanz der TextureBrush-Klasse mit einer Bilddatei. |
| [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Initialisiert eine neue Instanz der TextureBrush-Klasse mit der Bildstrom-Option. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | Liest oder setzt den Pfad zur Texturbilddatei. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Liest oder setzt den Pfad zur Texturbilddatei. |
| [getImageStream()](#getImageStream--) | Liest oder setzt den Bildstrom der Textur. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Liest oder setzt den Bildstrom der Textur. |
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Initialisiert eine neue Instanz der TextureBrush-Klasse mit Standardwerten.

### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Initialisiert eine neue Instanz der TextureBrush-Klasse mit einer Bilddatei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFilePath | java.lang.String | Pfad zur Bilddatei. |

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Initialisiert eine neue Instanz der TextureBrush-Klasse mit der Bildstrom-Option.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageStream | java.io.InputStream | Bildstrom. |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Liest oder setzt den Pfad zur Texturbilddatei. Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Liest oder setzt den Pfad zur Texturbilddatei. Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Liest oder setzt den Bildstrom der Textur. Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von ImageFilePath verwendet.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Liest oder setzt den Bildstrom der Textur. Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von ImageFilePath verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.io.InputStream |  |

