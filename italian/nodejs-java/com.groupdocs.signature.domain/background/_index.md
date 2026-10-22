---
title: "Sfondo"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta l'aspetto dello sfondo"
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Rappresenta l'aspetto dello sfondo
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Background()](#Background--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor()](#getColor--) | Ottiene o imposta il colore di sfondo della firma. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Ottiene o imposta il colore di sfondo della firma. |
| [setColor(String value)](#setColor-java.lang.String-) | Ottiene o imposta il colore di sfondo della firma. |
| [getTransparency()](#getTransparency--) | Ottiene o imposta la trasparenza dello sfondo (valore da 0.0 (opaco) a 1.0 (trasparente)). |
| [setTransparency(double value)](#setTransparency-double-) | Ottiene o imposta la trasparenza dello sfondo (valore da 0.0 (opaco) a 1.0 (trasparente)). |
| [getBrush()](#getBrush--) | Ottiene o imposta il pennello di sfondo. |
| [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Ottiene o imposta il pennello di sfondo. |
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


Ottiene o imposta il colore di sfondo della firma.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Ottiene o imposta il colore di sfondo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Ottiene o imposta il colore di sfondo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Ottiene o imposta la trasparenza dello sfondo (valore da 0.0 (opaco) a 1.0 (trasparente)).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Ottiene o imposta la trasparenza dello sfondo (valore da 0.0 (opaco) a 1.0 (trasparente)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Ottiene o imposta il pennello di sfondo. Il valore predefinito è null. Questa proprietà si aspetta istanze di implementazioni di oggetti Brush. Vedi le diverse classi Brush.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Ottiene o imposta il pennello di sfondo. Il valore predefinito è null. Questa proprietà si aspetta istanze di implementazioni di oggetti Brush. Vedi le diverse classi Brush.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

