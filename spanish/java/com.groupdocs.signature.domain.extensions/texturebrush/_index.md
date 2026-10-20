---
title: "TextureBrush"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa el pincel de textura."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Representa el pincel de textura.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextureBrush()](#TextureBrush--) | Inicializa una nueva instancia de la clase TextureBrush con valores predeterminados. |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Inicializa una nueva instancia de la clase TextureBrush con archivo de imagen. |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Inicializa una nueva instancia de la clase TextureBrush con opción de flujo de imagen. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Obtiene o establece la ruta del archivo de imagen de la textura. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Obtiene o establece la ruta del archivo de imagen de la textura. |
|
|  | [getImageStream()](#getImageStream--) | Obtiene o establece el flujo de imagen de la textura. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Obtiene o establece el flujo de imagen de la textura. |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Inicializa una nueva instancia de la clase TextureBrush con valores predeterminados.


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Inicializa una nueva instancia de la clase TextureBrush con archivo de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Ruta del archivo de imagen. |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Inicializa una nueva instancia de la clase TextureBrush con opción de flujo de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Flujo de imagen. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Obtiene o establece la ruta del archivo de imagen de la textura.
Esta propiedad se usa solo si ImageStream no está especificado.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Obtiene o establece la ruta del archivo de imagen de la textura.
Esta propiedad se usa solo si ImageStream no está especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Obtiene o establece el flujo de imagen de la textura.
Si esta propiedad está especificada, siempre se usa en lugar de ImageFilePath.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Obtiene o establece el flujo de imagen de la textura.
Si esta propiedad está especificada, siempre se usa en lugar de ImageFilePath.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.io.InputStream |  |

