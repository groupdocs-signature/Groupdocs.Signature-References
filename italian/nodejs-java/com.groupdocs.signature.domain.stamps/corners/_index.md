---
title: "Angoli"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta gli angoli di un oggetto grafico quadrato."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Rappresenta gli angoli di un oggetto grafico quadrato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Corners()](#Corners--) | Inizializza una nuova istanza della classe Corners usando valori zero. |
| [Corners(double all)](#Corners-double-) | Inizializza una nuova istanza della classe Corners usando il valore fornito per tutti gli angoli. |
| [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Inizializza una nuova istanza della classe Corners usando i valori forniti. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [Empty](#Empty) | Fornisce un oggetto Corners senza dati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAll()](#getAll--) | Ottiene o imposta il valore per tutti gli angoli. |
| [setAll(double value)](#setAll-double-) | Ottiene o imposta il valore per tutti gli angoli. |
| [getTopLeft()](#getTopLeft--) | Ottiene o imposta il valore dell'angolo in alto a sinistra. |
| [setTopLeft(double value)](#setTopLeft-double-) | Ottiene o imposta il valore dell'angolo in alto a sinistra. |
| [getTopRight()](#getTopRight--) | Ottiene o imposta il valore dell'angolo in alto a destra. |
| [setTopRight(double value)](#setTopRight-double-) | Ottiene o imposta il valore dell'angolo in alto a destra. |
| [getBottomLeft()](#getBottomLeft--) | Ottiene o imposta il valore dell'angolo in basso a sinistra. |
| [setBottomLeft(double value)](#setBottomLeft-double-) | Ottiene o imposta il valore dell'angolo in basso a sinistra. |
| [getBottomRight()](#getBottomRight--) | Ottiene o imposta il valore dell'angolo in basso a destra. |
| [setBottomRight(double value)](#setBottomRight-double-) | Ottiene o imposta il valore dell'angolo in basso a destra. |
| [deepClone()](#deepClone--) | Ottiene una copia di questo oggetto. |
| [equals(Object obj)](#equals-java.lang.Object-) | Sovrascrivi il metodo equals |
| [hashCode()](#hashCode--) | Sovrascrive l'ottenimento di un valore hash unico |
| [toString()](#toString--) | Sovrascrive la conversione in stringa. |
### Corners() {#Corners--}
```
public Corners()
```


Inizializza una nuova istanza della classe Corners usando valori zero.

### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Inizializza una nuova istanza della classe Corners usando il valore fornito per tutti gli angoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tutti | double | Il valore da utilizzare per il padding di tutti gli angoli. |

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Inizializza una nuova istanza della classe Corners usando i valori forniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| topLeft | double | Valore dell'angolo in alto a sinistra. |
| topRight | double | Valore dell'angolo in alto a destra. |
| bottomLeft | double | Valore dell'angolo in basso a sinistra. |
| bottomRight | double | Valore dell'angolo in basso a destra. |

### Empty {#Empty}
```
public static final Corners Empty
```


Fornisce un oggetto Corners senza dati.

### getAll() {#getAll--}
```
public final double getAll()
```


Ottiene o imposta il valore per tutti gli angoli. La modifica di qualsiasi angolo parziale, come l'angolo in alto a destra, rende questa proprietà uguale a 0;

**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Ottiene o imposta il valore per tutti gli angoli. La modifica di qualsiasi angolo parziale, come l'angolo in alto a destra, rende questa proprietà uguale a 0;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Ottiene o imposta il valore dell'angolo in alto a sinistra.

**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Ottiene o imposta il valore dell'angolo in alto a sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Ottiene o imposta il valore dell'angolo in alto a destra.

**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Ottiene o imposta il valore dell'angolo in alto a destra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Ottiene o imposta il valore dell'angolo in basso a sinistra.

**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Ottiene o imposta il valore dell'angolo in basso a sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Ottiene o imposta il valore dell'angolo in basso a destra.

**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Ottiene o imposta il valore dell'angolo in basso a destra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Ottiene una copia di questo oggetto.

**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Sovrascrivi il metodo equals

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Istanza con cui confrontare. |

**Returns:**
boolean - Restituisce true se le proprietà degli oggetti sono uguali.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive l'ottenimento di un valore hash unico

**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione in stringa.

**Returns:**
java.lang.String -
