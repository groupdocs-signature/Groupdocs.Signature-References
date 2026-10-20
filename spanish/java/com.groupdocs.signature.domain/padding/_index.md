---
title: "Padding"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa información de relleno o margen asociada al elemento."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Representa información de relleno o margen asociada al elemento.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Padding()](#Padding--) | Inicializa una nueva instancia de la clase Padding usando valores cero. |
|
|  | [Padding(int all)](#Padding-int-) | Inicializa una nueva instancia de la clase Padding usando el tamaño de relleno proporcionado para todos los bordes. |
|
|  | [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Inicializa una nueva instancia de la clase Padding usando los tamaños de relleno proporcionados. |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Empty](#Empty) | Proporciona un objeto Padding sin relleno. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAll()](#getAll--) | Obtiene o establece el valor de relleno para todos los bordes. |
|
|  | [setAll(int value)](#setAll-int-) | Obtiene o establece el valor de relleno para todos los bordes. |
|
|  | [getLeft()](#getLeft--) | Obtiene o establece el valor de relleno para el borde izquierdo. |
|
|  | [setLeft(int value)](#setLeft-int-) | Obtiene o establece el valor de relleno para el borde izquierdo. |
|
|  | [getRight()](#getRight--) | Obtiene o establece el valor de relleno para el borde derecho. |
|
|  | [setRight(int value)](#setRight-int-) | Obtiene o establece el valor de relleno para el borde derecho. |
|
|  | [getTop()](#getTop--) | Obtiene o establece el valor de relleno para el borde superior. |
|
|  | [setTop(int value)](#setTop-int-) | Obtiene o establece el valor de relleno para el borde superior. |
|
|  | [getBottom()](#getBottom--) | Obtiene o establece el valor de relleno para el borde inferior. |
|
|  | [setBottom(int value)](#setBottom-int-) | Obtiene o establece el valor de relleno para el borde inferior. |
|
|  | [getHorizontal()](#getHorizontal--) | Obtiene el relleno combinado para los bordes derecho e izquierdo. |
|
|  | [getVertical()](#getVertical--) | Obtiene el relleno combinado para los bordes superior e inferior. |
|
|  | [deepClone()](#deepClone--) | Obtiene una copia de este objeto. |
|
|  | [toString()](#toString--) | Sobrescribe la conversión a cadena |
|
### Padding() {#Padding--}
```
public Padding()
```


Inicializa una nueva instancia de la clase Padding usando valores cero.


### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Inicializa una nueva instancia de la clase Padding usando el tamaño de relleno proporcionado para todos los bordes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | todos | int | El número de unidades de medida que se usarán para el relleno en todos los bordes. |
|

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Inicializa una nueva instancia de la clase Padding usando los tamaños de relleno proporcionados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | izquierda | int | El tamaño del relleno izquierdo. |
|
|  | derecha | int | El tamaño del relleno derecho. |
|
|  | superior | int | El tamaño del relleno superior. |
|
|  | inferior | int | El tamaño del relleno inferior. |
|

### Empty {#Empty}
```
public static final Padding Empty
```


Proporciona un objeto Padding sin relleno.


### getAll() {#getAll--}
```
public final int getAll()
```


Obtiene o establece el valor de relleno para todos los bordes.
Cambiar cualquier borde parcial, como el izquierdo o el superior, hace que esta propiedad sea igual a 0;


**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Obtiene o establece el valor de relleno para todos los bordes.
Cambiar cualquier borde parcial, como el izquierdo o el superior, hace que esta propiedad sea igual a 0;


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Obtiene o establece el valor de relleno para el borde izquierdo.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Obtiene o establece el valor de relleno para el borde izquierdo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Obtiene o establece el valor de relleno para el borde derecho.


**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Obtiene o establece el valor de relleno para el borde derecho.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Obtiene o establece el valor de relleno para el borde superior.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Obtiene o establece el valor de relleno para el borde superior.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Obtiene o establece el valor de relleno para el borde inferior.


**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Obtiene o establece el valor de relleno para el borde inferior.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Obtiene el relleno combinado para los bordes derecho e izquierdo.


**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Obtiene el relleno combinado para los bordes superior e inferior.


**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Obtiene una copia de este objeto.


**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Sobrescribe la conversión a cadena


**Returns:**
java.lang.String - 
