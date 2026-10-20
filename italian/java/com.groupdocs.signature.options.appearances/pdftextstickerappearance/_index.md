---
title: "PdfTextStickerAppearance"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Descrive l'aspetto dell'oggetto adesivo di annotazione testo PDF e della finestra pop-up dell'adesivo."
type: docs
weight: 14
url: /it/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

Descrive l'aspetto dell'oggetto adesivo di annotazione testo PDF e della finestra pop-up dell'adesivo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | Crea l'oggetto di aspetto dell'annotazione di testo della firma PDF. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getTitle()](#getTitle--) | Ottiene o imposta il titolo della finestra pop-up. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Ottiene o imposta il titolo della finestra pop-up. |
|
|  | [getSubject()](#getSubject--) | Ottiene o imposta l'oggetto. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Ottiene o imposta l'oggetto. |
|
|  | [getContents()](#getContents--) | Ottiene o imposta il contenuto della finestra pop-up. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Ottiene o imposta il contenuto della finestra pop-up. |
|
|  | [getOpened()](#getOpened--) | Imposta se la finestra pop-up dell'adesivo sarà aperta per impostazione predefinita. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | Imposta se la finestra pop-up dell'adesivo sarà aperta per impostazione predefinita. |
|
|  | [getIcon()](#getIcon--) | Ottiene o imposta l'icona dell'adesivo. |
|
|  | [setIcon(int value)](#setIcon-int-) | Ottiene o imposta l'icona dell'adesivo. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | Ottiene l'aspetto predefinito per l'adesivo. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | Cancella i valori dell'aspetto predefinito per l'adesivo. |
|
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


Crea l'oggetto di aspetto dell'annotazione di testo della firma PDF.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


Ottiene o imposta il titolo della finestra pop-up.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Ottiene o imposta il titolo della finestra pop-up.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Ottiene o imposta l'oggetto.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Ottiene o imposta l'oggetto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


Ottiene o imposta il contenuto della finestra pop-up.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Ottiene o imposta il contenuto della finestra pop-up.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


Imposta se la finestra pop-up dell'adesivo sarà aperta per impostazione predefinita.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


Imposta se la finestra pop-up dell'adesivo sarà aperta per impostazione predefinita.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


Ottiene o imposta l'icona dell'adesivo.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


Ottiene o imposta l'icona dell'adesivo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


Ottiene l'aspetto predefinito per l'adesivo. Queste proprietà sono applicate come predefinite se
La proprietà Options.SignatureAppearance non è specificata.
Le proprietà possono essere modificate dall'utente in qualsiasi momento.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


Cancella i valori dell'aspetto predefinito per l'adesivo.


### toString() {#toString--}
```
public String toString()
```


Sovrascrivi la conversione di stringa.


**Returns:**
java.lang.String -
