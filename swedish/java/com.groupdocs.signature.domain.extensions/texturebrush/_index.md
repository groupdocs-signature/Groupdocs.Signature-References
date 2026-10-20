---
title: "TextureBrush"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar texturpensel."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Representerar texturpensel.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [TextureBrush()](#TextureBrush--) | Initierar en ny instans av klassen TextureBrush med standardvärden. |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Initierar en ny instans av klassen TextureBrush med bildfil. |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Initierar en ny instans av klassen TextureBrush med bildström‑alternativ. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Hämtar eller anger sökvägen till texturens bildfil. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Hämtar eller anger sökvägen till texturens bildfil. |
|
|  | [getImageStream()](#getImageStream--) | Hämtar eller anger texturens bildström. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Hämtar eller anger texturens bildström. |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Initierar en ny instans av klassen TextureBrush med standardvärden.


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Initierar en ny instans av klassen TextureBrush med bildfil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Sökväg till bildfil. |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Initierar en ny instans av klassen TextureBrush med bildström‑alternativ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Bildström. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Hämtar eller anger sökvägen till texturens bildfil.
Denna egenskap används endast om ImageStream inte är angiven.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Hämtar eller anger sökvägen till texturens bildfil.
Denna egenskap används endast om ImageStream inte är angiven.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Hämtar eller anger texturens bildström.
Om denna egenskap är angiven används den alltid i stället för ImageFilePath.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Hämtar eller anger texturens bildström.
Om denna egenskap är angiven används den alltid i stället för ImageFilePath.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.io.InputStream |  |

