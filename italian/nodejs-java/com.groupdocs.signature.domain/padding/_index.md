---
title: "Padding"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le informazioni di padding o margine associate all'elemento."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Rappresenta le informazioni di padding o margine associate all'elemento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Padding()](#Padding--) | Inizializza una nuova istanza della classe Padding usando valori zero. |
| [Padding(int all)](#Padding-int-) | Inizializza una nuova istanza della classe Padding usando la dimensione di padding fornita per tutti i bordi. |
| [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Inizializza una nuova istanza della classe Padding usando le dimensioni di padding fornite. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [Empty](#Empty) | Fornisce un oggetto Padding senza padding. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAll()](#getAll--) | Ottiene o imposta il valore di padding per tutti i bordi. |
| [setAll(int value)](#setAll-int-) | Ottiene o imposta il valore di padding per tutti i bordi. |
| [getLeft()](#getLeft--) | Ottiene o imposta il valore di padding per il bordo sinistro. |
| [setLeft(int value)](#setLeft-int-) | Ottiene o imposta il valore di padding per il bordo sinistro. |
| [getRight()](#getRight--) | Ottiene o imposta il valore di padding per il bordo destro. |
| [setRight(int value)](#setRight-int-) | Ottiene o imposta il valore di padding per il bordo destro. |
| [getTop()](#getTop--) | Ottiene o imposta il valore di padding per il bordo superiore. |
| [setTop(int value)](#setTop-int-) | Ottiene o imposta il valore di padding per il bordo superiore. |
| [getBottom()](#getBottom--) | Ottiene o imposta il valore di padding per il bordo inferiore. |
| [setBottom(int value)](#setBottom-int-) | Ottiene o imposta il valore di padding per il bordo inferiore. |
| [getHorizontal()](#getHorizontal--) | Ottiene il padding combinato per i bordi destro e sinistro. |
| [getVertical()](#getVertical--) | Ottiene il padding combinato per i bordi superiore e inferiore. |
| [deepClone()](#deepClone--) | Ottiene una copia di questo oggetto. |
| [toString()](#toString--) | Sovrascrive la conversione in stringa |
### Padding() {#Padding--}
```
public Padding()
```


Inizializza una nuova istanza della classe Padding usando valori zero.

### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Inizializza una nuova istanza della classe Padding usando la dimensione di padding fornita per tutti i bordi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tutti | int | Il numero di unità di misura da utilizzare per il padding su tutti i bordi. |

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Inizializza una nuova istanza della classe Padding usando le dimensioni di padding fornite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | int | La dimensione del padding sinistro. |
| destra | int | La dimensione del padding destro. |
| alto | int | La dimensione del padding superiore. |
| inferiore | int | La dimensione del padding inferiore. |

### Empty {#Empty}
```
public static final Padding Empty
```


Fornisce un oggetto Padding senza padding.

### getAll() {#getAll--}
```
public final int getAll()
```


Ottiene o imposta il valore del padding per tutti i bordi. La modifica di un qualsiasi bordo parziale, come sinistro o superiore, imposta questa proprietà a 0;

**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Ottiene o imposta il valore del padding per tutti i bordi. La modifica di un qualsiasi bordo parziale, come sinistro o superiore, imposta questa proprietà a 0;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ottiene o imposta il valore di padding per il bordo sinistro.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Ottiene o imposta il valore di padding per il bordo sinistro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Ottiene o imposta il valore di padding per il bordo destro.

**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Ottiene o imposta il valore di padding per il bordo destro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Ottiene o imposta il valore di padding per il bordo superiore.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Ottiene o imposta il valore di padding per il bordo superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Ottiene o imposta il valore di padding per il bordo inferiore.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Ottiene o imposta il valore di padding per il bordo inferiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Ottiene il padding combinato per i bordi destro e sinistro.

**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Ottiene il padding combinato per i bordi superiore e inferiore.

**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Ottiene una copia di questo oggetto.

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione in stringa

**Returns:**
java.lang.String -
