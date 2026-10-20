---
title: "Background"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa la apariencia de fondo"
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Representa la apariencia de fondo

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Background()](#Background--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getColor()](#getColor--) | Obtiene o establece el color de fondo de la firma. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Obtiene o establece el color de fondo de la firma. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Obtiene o establece el color de fondo de la firma. |
|
|  | [getTransparency()](#getTransparency--) | Obtiene o establece la transparencia del fondo (valor de 0.0 (opaco) a 1.0 (claro)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Obtiene o establece la transparencia del fondo (valor de 0.0 (opaco) a 1.0 (claro)). |
|
|  | [getBrush()](#getBrush--) | Obtiene o establece el pincel de fondo. |
|
|  | [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Obtiene o establece el pincel de fondo. |
|
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


Obtiene o establece el color de fondo de la firma.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Obtiene o establece el color de fondo de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Obtiene o establece el color de fondo de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Obtiene o establece la transparencia del fondo (valor de 0.0 (opaco) a 1.0 (claro)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Obtiene o establece la transparencia del fondo (valor de 0.0 (opaco) a 1.0 (claro)).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Obtiene o establece el pincel de fondo. El valor por defecto es null.
Esta propiedad espera una instancia de implementaciones de objetos Brush
Ver diferentes clases Brush


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Obtiene o establece el pincel de fondo. El valor por defecto es null.
Esta propiedad espera una instancia de implementaciones de objetos Brush
Ver diferentes clases Brush


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

