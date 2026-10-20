---
title: "TextShadow"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta le proprietà dell'ombra del testo per le firme di testo."
type: docs
weight: 13
url: /it/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

Rappresenta le proprietà dell'ombra del testo per le firme di testo.
Il risultato può variare a seconda del tipo di firma e del formato del documento.
TextShadow è consigliato per l'uso con la firma TextAsImage per tutti i tipi di documento supportati,
anche con TextSignature semplice e TextSignature come filigrana per Cells (.xslx) e Slides (.pptx).
TextSignature semplice per Words (.docx) è consigliato anche, ma ha funzionalità limitate.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | Crea TextShadow con le opzioni predefinite. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getDistance()](#getDistance--) | Ottiene o imposta la distanza dal testo all'ombra. |
|
|  | [setDistance(double value)](#setDistance-double-) | Ottiene o imposta la distanza dal testo all'ombra. |
|
|  | [getAngle()](#getAngle--) | Ottiene o imposta l'angolo per posizionare l'ombra rispetto al testo. |
|
|  | [setAngle(double value)](#setAngle-double-) | Ottiene o imposta l'angolo per posizionare l'ombra rispetto al testo. |
|
|  | [getColor()](#getColor--) | Ottiene o imposta il colore dell'ombra. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Ottiene o imposta il colore dell'ombra. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | Ottiene o imposta il colore dell'ombra. |
|
|  | [getTransparency()](#getTransparency--) | Ottiene o imposta la trasparenza dell'ombra. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Ottiene o imposta la trasparenza dell'ombra. |
|
|  | [getBlur()](#getBlur--) | Ottiene o imposta la sfocatura dell'ombra. |
|
|  | [setBlur(double value)](#setBlur-double-) | Ottiene o imposta la sfocatura dell'ombra. |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


Crea TextShadow con le opzioni predefinite.


### getDistance() {#getDistance--}
```
public final double getDistance()
```


Ottiene o imposta la distanza dal testo all'ombra.
Il valore predefinito è 1.


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Ottiene o imposta la distanza dal testo all'ombra.
Il valore predefinito è 1.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


Ottiene o imposta l'angolo per posizionare l'ombra rispetto al testo.
Il valore predefinito è 0.


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Ottiene o imposta l'angolo per posizionare l'ombra rispetto al testo.
Il valore predefinito è 0.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


Ottiene o imposta il colore dell'ombra.
Il valore predefinito è Nero.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Ottiene o imposta il colore dell'ombra.
Il valore predefinito è Nero.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


Ottiene o imposta il colore dell'ombra.
Il valore predefinito è Nero.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Ottiene o imposta la trasparenza dell'ombra.
Il valore predefinito è 0.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Ottiene o imposta la trasparenza dell'ombra.
Il valore predefinito è 0.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


Ottiene o imposta la sfocatura dell'ombra.
Il valore predefinito è 4.


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


Ottiene o imposta la sfocatura dell'ombra.
Il valore predefinito è 4.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

