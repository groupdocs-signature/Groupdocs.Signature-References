---
title: "PdfTextAnnotationAppearance"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Descrive l'aspetto dell'oggetto annotazione di testo PDF Titolo Soggetto Contenuto."
type: docs
weight: 13
url: /it/java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

Descrive l'aspetto dell'oggetto di annotazione testo PDF (Titolo, Soggetto, Contenuto).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | Crea l'oggetto aspetto dell'annotazione di testo della firma PDF. |
|
|  | [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | Crea l'annotazione di testo della firma PDF con i valori specificati (titolo, soggetto, contenuti). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getContents()](#getContents--) | Ottiene o imposta il contenuto dell'oggetto annotazione. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | Ottiene o imposta il contenuto dell'oggetto annotazione. |
|
|  | [getSubject()](#getSubject--) | Ottiene o imposta il Soggetto che rappresenta la descrizione dell'oggetto. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Ottiene o imposta il Soggetto che rappresenta la descrizione dell'oggetto. |
|
|  | [getTitle()](#getTitle--) | Ottiene o imposta un Titolo che verrà visualizzato nella barra del titolo dell'oggetto di annotazione. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Ottiene o imposta un Titolo che verrà visualizzato nella barra del titolo dell'oggetto di annotazione. |
|
|  | [getBorder()](#getBorder--) | Ottiene o imposta diverse impostazioni del bordo |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Ottiene o imposta diverse impostazioni del bordo |
|
|  | [getBorderEffect()](#getBorderEffect--) | Ottiene o imposta l'effetto del bordo. |
|
|  | [setBorderEffect(int value)](#setBorderEffect-int-) | Ottiene o imposta l'effetto del bordo. |
|
|  | [getBorderEffectIntensity()](#getBorderEffectIntensity--) | Ottiene o imposta l'intensità dell'effetto del bordo. |
|
|  | [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | Ottiene o imposta l'intensità dell'effetto del bordo. |
|
|  | [getHCornerRadius()](#getHCornerRadius--) | Ottiene o imposta il raggio dell'angolo orizzontale. |
|
|  | [setHCornerRadius(int value)](#setHCornerRadius-int-) | Ottiene o imposta il raggio dell'angolo orizzontale. |
|
|  | [getVCornerRadius()](#getVCornerRadius--) | Ottiene o imposta il raggio dell'angolo verticale. |
|
|  | [setVCornerRadius(int value)](#setVCornerRadius-int-) | Ottiene o imposta il raggio dell'angolo verticale. |
|
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa. |
|
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


Crea l'oggetto aspetto dell'annotazione di testo della firma PDF.


### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


Crea l'annotazione di testo della firma PDF con i valori specificati (titolo, soggetto, contenuti).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | titolo | java.lang.String | Titolo. |
|
|  | oggetto | java.lang.String | Oggetto. |
|
|  | contenuti | java.lang.String | Contenuti. |
|

### getContents() {#getContents--}
```
public final String getContents()
```


Ottiene o imposta il contenuto dell'oggetto annotazione.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


Ottiene o imposta il contenuto dell'oggetto annotazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Ottiene o imposta il Soggetto che rappresenta la descrizione dell'oggetto.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Ottiene o imposta il Soggetto che rappresenta la descrizione dell'oggetto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Ottiene o imposta un Titolo che verrà visualizzato nella barra del titolo dell'oggetto di annotazione.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Ottiene o imposta un Titolo che verrà visualizzato nella barra del titolo dell'oggetto di annotazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Ottiene o imposta diverse impostazioni del bordo


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Ottiene o imposta diverse impostazioni del bordo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


Ottiene o imposta l'effetto del bordo.


**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


Ottiene o imposta l'effetto del bordo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


Ottiene o imposta l'intensità dell'effetto del bordo. L'intervallo valido del valore è [0..2].


**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


Ottiene o imposta l'intensità dell'effetto del bordo. L'intervallo valido del valore è [0..2].


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


Ottiene o imposta il raggio dell'angolo orizzontale.


**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


Ottiene o imposta il raggio dell'angolo orizzontale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


Ottiene o imposta il raggio dell'angolo verticale.


**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


Ottiene o imposta il raggio dell'angolo verticale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrivi la conversione di stringa.


**Returns:**
java.lang.String -
