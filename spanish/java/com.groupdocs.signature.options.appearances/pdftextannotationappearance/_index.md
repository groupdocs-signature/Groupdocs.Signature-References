---
title: "PdfTextAnnotationAppearance"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Describe la apariencia del objeto de anotación de texto PDF Título Asunto Contenido."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Describe la apariencia del objeto de anotación de texto PDF (Título, Asunto, Contenido).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Crea un objeto de apariencia de anotación de texto de firma PDF. |
|
|  | [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Crea una anotación de texto de firma PDF con valores especificados (title, subject, contents). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getContents()](#getContents--) | Obtiene o establece el contenido del objeto de anotación. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Obtiene o establece el contenido del objeto de anotación. |
|
|  | [getSubject()](#getSubject--) | Obtiene o establece Subject que representa la descripción del objeto. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Obtiene o establece Subject que representa la descripción del objeto. |
|
|  | [getTitle()](#getTitle--) | Obtiene o establece un Title que se mostrará en la barra de título del objeto de anotación. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Obtiene o establece un Title que se mostrará en la barra de título del objeto de anotación. |
|
|  | [getBorder()](#getBorder--) | Obtiene o establece diferentes configuraciones de borde |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Obtiene o establece diferentes configuraciones de borde |
|
|  | [getBorderEffect()](#getBorderEffect--) | Obtiene o establece el efecto de borde. |
|
|  | [setBorderEffect(int value)](#setBorderEffect-int-) | Obtiene o establece el efecto de borde. |
|
|  | [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Obtiene o establece la intensidad del efecto de borde. |
|
|  | [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Obtiene o establece la intensidad del efecto de borde. |
|
|  | [getHCornerRadius()](#getHCornerRadius--) | Obtiene o establece el radio de esquina horizontal. |
|
|  | [setHCornerRadius(int value)](#setHCornerRadius-int-) | Obtiene o establece el radio de esquina horizontal. |
|
|  | [getVCornerRadius()](#getVCornerRadius--) | Obtiene o establece el radio de esquina vertical |
|
|  | [setVCornerRadius(int value)](#setVCornerRadius-int-) | Obtiene o establece el radio de esquina vertical |
|
|  | [toString()](#toString--) | Sobrescribir conversión de cadena. |
|
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Crea un objeto de apariencia de anotación de texto de firma PDF.


### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Crea una anotación de texto de firma PDF con valores especificados (title, subject, contents).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | título | java.lang.String | Título. |
|
|  | asunto | java.lang.String | Asunto. |
|
|  | contenidos | java.lang.String | Contenidos. |
|

### getContents() {#getContents--}
```
public final String getContents()
```


Obtiene o establece el contenido del objeto de anotación.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Obtiene o establece el contenido del objeto de anotación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Obtiene o establece Subject que representa la descripción del objeto.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Obtiene o establece Subject que representa la descripción del objeto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Obtiene o establece un Title que se mostrará en la barra de título del objeto de anotación.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Obtiene o establece un Title que se mostrará en la barra de título del objeto de anotación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Obtiene o establece diferentes configuraciones de borde


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Obtiene o establece diferentes configuraciones de borde


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Obtiene o establece el efecto de borde.


**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Obtiene o establece el efecto de borde.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Obtiene o establece la intensidad del efecto de borde. El rango válido del valor es [0..2].


**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Obtiene o establece la intensidad del efecto de borde. El rango válido del valor es [0..2].


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Obtiene o establece el radio de esquina horizontal.


**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Obtiene o establece el radio de esquina horizontal.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Obtiene o establece el radio de esquina vertical


**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Obtiene o establece el radio de esquina vertical


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### toString() {#toString--}
```
public String toString()
```


Sobrescribir conversión de cadena.


**Returns:**
java.lang.String - 
