---
title: "Borde"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Instancia para mantener las propiedades de la línea de borde."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Instancia para mantener las propiedades de la línea de borde.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Border()](#Border--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | Obtiene o establece el estilo del borde de la firma. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Obtiene o establece el estilo del borde de la firma. |
|
|  | [getTransparency()](#getTransparency--) | Obtiene o establece la transparencia del borde de la firma (valor de 0.0 (opaco) a 1.0 (claro)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Obtiene o establece la transparencia del borde de la firma (valor de 0.0 (opaco) a 1.0 (claro)). |
|
|  | [getWeight()](#getWeight--) | Obtiene o establece el grosor del borde de la firma. |
|
|  | [setWeight(double value)](#setWeight-double-) | Obtiene o establece el grosor del borde de la firma. |
|
|  | [getColor()](#getColor--) | Obtiene o establece el color del borde de la firma. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Obtiene o establece el color del borde de la firma. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Obtiene o establece el color del borde de la firma. |
|
|  | [getVisible()](#getVisible--) | Obtiene o establece la visibilidad del borde. |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | Implementa la interfaz IClonable |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Obtiene o establece el estilo del borde de la firma.


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Obtiene o establece el estilo del borde de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Obtiene o establece la transparencia del borde de la firma (valor de 0.0 (opaco) a 1.0 (claro)).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Obtiene o establece la transparencia del borde de la firma (valor de 0.0 (opaco) a 1.0 (claro)).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Obtiene o establece el grosor del borde de la firma.


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Obtiene o establece el grosor del borde de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Obtiene o establece el color del borde de la firma.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Obtiene o establece el color del borde de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Obtiene o establece el color del borde de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Obtiene o establece la visibilidad del borde.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Implementa la interfaz IClonable


**Returns:**
java.lang.Object - Nueva instancia de Border creada con las mismas propiedades

