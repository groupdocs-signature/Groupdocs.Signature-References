---
title: "TextureBrush"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Stelt textuurpenseel voor."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Stelt textuurpenseel voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextureBrush()](#TextureBrush--) | Initialiseert een nieuw exemplaar van de TextureBrush-klasse met standaardwaarden. |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Initialiseert een nieuw exemplaar van de TextureBrush-klasse met een afbeeldingsbestand. |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de TextureBrush-klasse met de optie afbeeldingstroom. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Haalt of stelt het bestandspad van de textuurafbeelding in. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Haalt of stelt het bestandspad van de textuurafbeelding in. |
|
|  | [getImageStream()](#getImageStream--) | Haalt de textuurafbeeldingsstroom op of stelt deze in. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Haalt de textuurafbeeldingsstroom op of stelt deze in. |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Initialiseert een nieuw exemplaar van de TextureBrush-klasse met standaardwaarden.


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Initialiseert een nieuw exemplaar van de TextureBrush-klasse met een afbeeldingsbestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Pad naar afbeeldingsbestand. |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Initialiseert een nieuw exemplaar van de TextureBrush-klasse met de optie afbeeldingstroom.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Afbeeldingsstroom. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Haalt of stelt het bestandspad van de textuurafbeelding in.
Deze eigenschap wordt alleen gebruikt als ImageStream niet is opgegeven.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Haalt of stelt het bestandspad van de textuurafbeelding in.
Deze eigenschap wordt alleen gebruikt als ImageStream niet is opgegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Haalt de textuurafbeeldingsstroom op of stelt deze in.
Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van ImageFilePath.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Haalt de textuurafbeeldingsstroom op of stelt deze in.
Als deze eigenschap is opgegeven, wordt deze altijd gebruikt in plaats van ImageFilePath.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.io.InputStream |  |

