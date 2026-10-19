---
title: "TextureBrush"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt einen Texturpinsel dar."
type: docs
weight: 14
url: /de/java/com.groupdocs.signature.domain.extensions/texturebrush/
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
|  | [TextureBrush()](#TextureBrush--) | Initialisiert eine neue Instanz der Klasse TextureBrush mit Standardwerten. |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Initialisiert eine neue Instanz der Klasse TextureBrush mit einer Bilddatei. |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse TextureBrush mit Bildstrom-Option. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Ruft den Pfad zur Texturbilddatei ab oder legt ihn fest. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Ruft den Pfad zur Texturbilddatei ab oder legt ihn fest. |
|
|  | [getImageStream()](#getImageStream--) | Liest oder setzt den Textur‑Bild‑Stream. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Liest oder setzt den Textur‑Bild‑Stream. |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Initialisiert eine neue Instanz der Klasse TextureBrush mit Standardwerten.


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Initialisiert eine neue Instanz der Klasse TextureBrush mit einer Bilddatei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Bilddateipfad. |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Initialisiert eine neue Instanz der Klasse TextureBrush mit Bildstrom-Option.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Bild‑Stream. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Ruft den Pfad zur Texturbilddatei ab oder legt ihn fest.
Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Ruft den Pfad zur Texturbilddatei ab oder legt ihn fest.
Diese Eigenschaft wird nur verwendet, wenn ImageStream nicht angegeben ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Liest oder setzt den Textur‑Bild‑Stream.
Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von ImageFilePath verwendet.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Liest oder setzt den Textur‑Bild‑Stream.
Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von ImageFilePath verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.io.InputStream |  |

