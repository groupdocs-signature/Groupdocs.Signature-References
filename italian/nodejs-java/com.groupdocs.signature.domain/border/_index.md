---
title: "Bordo"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Istanza per mantenere le proprietà della linea del bordo."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Istanza per mantenere le proprietà della linea del bordo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Border()](#Border--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDashStyle()](#getDashStyle--) | Ottiene o imposta lo stile del bordo della firma. |
| [setDashStyle(int value)](#setDashStyle-int-) | Ottiene o imposta lo stile del bordo della firma. |
| [getTransparency()](#getTransparency--) | Ottiene o imposta la trasparenza del bordo della firma (valore da 0.0 (opaco) a 1.0 (trasparente)). |
| [setTransparency(double value)](#setTransparency-double-) | Ottiene o imposta la trasparenza del bordo della firma (valore da 0.0 (opaco) a 1.0 (trasparente)). |
| [getWeight()](#getWeight--) | Ottiene o imposta lo spessore del bordo della firma. |
| [setWeight(double value)](#setWeight-double-) | Ottiene o imposta lo spessore del bordo della firma. |
| [getColor()](#getColor--) | Ottiene o imposta il colore del bordo della firma. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Ottiene o imposta il colore del bordo della firma. |
| [setColor(String value)](#setColor-java.lang.String-) | Ottiene o imposta il colore del bordo della firma. |
| [getVisible()](#getVisible--) | Ottiene o imposta la visibilità del bordo. |
| [setVisible(boolean value)](#setVisible-boolean-) |  |
| [deepClone()](#deepClone--) | Implementa l'interfaccia IClonable |
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Ottiene o imposta lo stile del bordo della firma.

**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Ottiene o imposta lo stile del bordo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Ottiene o imposta la trasparenza del bordo della firma (valore da 0.0 (opaco) a 1.0 (trasparente)).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Ottiene o imposta la trasparenza del bordo della firma (valore da 0.0 (opaco) a 1.0 (trasparente)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


Ottiene o imposta lo spessore del bordo della firma.

**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Ottiene o imposta lo spessore del bordo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Ottiene o imposta il colore del bordo della firma.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Ottiene o imposta il colore del bordo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Ottiene o imposta il colore del bordo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Ottiene o imposta la visibilità del bordo.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Implementa l'interfaccia IClonable

**Returns:**
java.lang.Object - Nuova istanza di Border creata con le stesse proprietà
