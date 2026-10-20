---
title: "PdfTextStickerAppearance"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Describe la apariencia del objeto adhesivo de anotación de texto PDF y la ventana emergente del adhesivo."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

Describe la apariencia del objeto adhesivo de anotación de texto PDF y la ventana emergente del adhesivo.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | Crea un objeto de apariencia de anotación de texto de firma PDF. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getTitle()](#getTitle--) | Obtiene o establece el título de la ventana emergente. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Obtiene o establece el título de la ventana emergente. |
|
|  | [getSubject()](#getSubject--) | Obtiene o establece el asunto. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Obtiene o establece el asunto. |
|
|  | [getContents()](#getContents--) | Obtiene o establece el contenido de la ventana emergente. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Obtiene o establece el contenido de la ventana emergente. |
|
|  | [getOpened()](#getOpened--) | Configurar si la ventana emergente de sticker se abrirá por defecto. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | Configurar si la ventana emergente de sticker se abrirá por defecto. |
|
|  | [getIcon()](#getIcon--) | Obtiene o establece el ícono de sticker. |
|
|  | [setIcon(int value)](#setIcon-int-) | Obtiene o establece el ícono de sticker. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | Obtiene la apariencia predeterminada de sticker. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | Borra los valores de la apariencia predeterminada de sticker. |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


Crea un objeto de apariencia de anotación de texto de firma PDF.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


Obtiene o establece el título de la ventana emergente.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Obtiene o establece el título de la ventana emergente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Obtiene o establece el asunto.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Obtiene o establece el asunto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Obtiene o establece el contenido de la ventana emergente.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Obtiene o establece el contenido de la ventana emergente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Configurar si la ventana emergente de sticker se abrirá por defecto.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Configurar si la ventana emergente de sticker se abrirá por defecto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Obtiene o establece el ícono de sticker.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Obtiene o establece el ícono de sticker.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Obtiene la apariencia predeterminada de sticker. Estas propiedades se aplican como predeterminadas si
La propiedad Options.SignatureAppearance no está especificada.
Las propiedades pueden ser cambiadas por el usuario en cualquier momento.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Borra los valores de la apariencia predeterminada de sticker.


### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
