---
title: "Esquinas"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa las esquinas de un objeto gráfico cuadrado."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Representa las esquinas de un objeto gráfico cuadrado.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Corners()](#Corners--) | Inicializa una nueva instancia de la clase Corners usando valores cero. |
|
|  | [Corners(double all)](#Corners-double-) | Inicializa una nueva instancia de la clase Corners usando el valor proporcionado para todas las esquinas. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Inicializa una nueva instancia de la clase Corners usando los valores proporcionados. |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Empty](#Empty) | Proporciona un objeto Corners sin datos. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAll()](#getAll--) | Obtiene o establece el valor para todas las esquinas. |
|
|  | [setAll(double value)](#setAll-double-) | Obtiene o establece el valor para todas las esquinas. |
|
|  | [getTopLeft()](#getTopLeft--) | Obtiene o establece el valor de la esquina superior izquierda. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | Obtiene o establece el valor de la esquina superior izquierda. |
|
|  | [getTopRight()](#getTopRight--) | Obtiene o establece el valor de la esquina superior derecha. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | Obtiene o establece el valor de la esquina superior derecha. |
|
|  | [getBottomLeft()](#getBottomLeft--) | Obtiene o establece el valor de la esquina inferior izquierda. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | Obtiene o establece el valor de la esquina inferior izquierda. |
|
|  | [getBottomRight()](#getBottomRight--) | Obtiene o establece el valor de la esquina inferior derecha. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | Obtiene o establece el valor de la esquina inferior derecha. |
|
|  | [deepClone()](#deepClone--) | Obtiene una copia de este objeto. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Sobrescribir el método equals |
|
|  | [hashCode()](#hashCode--) | Sobrescribe la obtención del valor único del código hash |
|
|  | [toString()](#toString--) | Sobrescribe la conversión a cadena. |
|
### Corners() {#Corners--}
```
public Corners()
```


Inicializa una nueva instancia de la clase Corners usando valores cero.


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Inicializa una nueva instancia de la clase Corners usando el valor proporcionado para todas las esquinas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | todos | double | El valor a usar como relleno para todas las esquinas. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Inicializa una nueva instancia de la clase Corners usando los valores proporcionados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | topLeft | double | Valor de la esquina superior izquierda. |
|
|  | topRight | double | Valor de la esquina superior derecha. |
|
|  | bottomLeft | double | Valor de la esquina inferior izquierda. |
|
|  | bottomRight | double | Valor de la esquina inferior derecha. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


Proporciona un objeto Corners sin datos.


### getAll() {#getAll--}
```
public final double getAll()
```


Obtiene o establece el valor para todas las esquinas.
Cambiar cualquier esquina parcial, como la superior derecha, hace que esta propiedad sea igual a 0;


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Obtiene o establece el valor para todas las esquinas.
Cambiar cualquier esquina parcial, como la superior derecha, hace que esta propiedad sea igual a 0;


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Obtiene o establece el valor de la esquina superior izquierda.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Obtiene o establece el valor de la esquina superior izquierda.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Obtiene o establece el valor de la esquina superior derecha.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Obtiene o establece el valor de la esquina superior derecha.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Obtiene o establece el valor de la esquina inferior izquierda.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Obtiene o establece el valor de la esquina inferior izquierda.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Obtiene o establece el valor de la esquina inferior derecha.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Obtiene o establece el valor de la esquina inferior derecha.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Obtiene una copia de este objeto.


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Sobrescribir el método equals


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Instancia con la que comparar. |
|

**Returns:**
boolean - Devuelve true si las propiedades de los objetos son iguales.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sobrescribe la obtención del valor único del código hash


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Sobrescribe la conversión a cadena.


**Returns:**
java.lang.String - 
