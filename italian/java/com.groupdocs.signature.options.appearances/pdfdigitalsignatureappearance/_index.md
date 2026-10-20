---
title: "PdfDigitalSignatureAppearance"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Descrive l'aspetto della firma digitale nei documenti PDF."
type: docs
weight: 12
url: /it/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Descrive l'aspetto della firma digitale nei documenti PDF.

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Crea un oggetto di aspetto della firma con valori predefiniti. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | Ottiene o imposta l'etichetta delle informazioni di contatto. |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Ottiene o imposta l'etichetta delle informazioni di contatto. |
|
|  | [getReasonLabel()](#getReasonLabel--) | Ottiene o imposta l'etichetta del motivo. |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Ottiene o imposta l'etichetta del motivo. |
|
|  | [getLocationLabel()](#getLocationLabel--) | Ottiene o imposta l'etichetta della posizione. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Ottiene o imposta l'etichetta della posizione. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Ottiene o imposta l'etichetta firmata digitalmente. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Ottiene o imposta l'etichetta firmata digitalmente. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Ottiene o imposta l'etichetta della data di firma. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Ottiene o imposta l'etichetta della data di firma. |
|
|  | [getBackground()](#getBackground--) | Ottieni o imposta il colore di sfondo dell'aspetto della firma. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | Ottieni o imposta il colore di sfondo dell'aspetto della firma. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | Ottieni o imposta il colore di sfondo dell'aspetto della firma. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | Ottiene o imposta il nome della famiglia di caratteri per visualizzare le etichette. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Ottiene o imposta il nome della famiglia di caratteri per visualizzare le etichette. |
|
|  | [getFontSize()](#getFontSize--) | Ottiene o imposta la dimensione del carattere per visualizzare le etichette. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | Ottiene o imposta la dimensione del carattere per visualizzare le etichette. |
|
|  | [getForeground()](#getForeground--) | Ottieni o imposta il colore del testo in primo piano dell'aspetto della firma. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | Ottieni o imposta il colore del testo in primo piano dell'aspetto della firma. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | Ottieni o imposta il colore del testo in primo piano dell'aspetto della firma. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Crea un oggetto di aspetto della firma con valori predefiniti.


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Ottiene o imposta l'etichetta delle informazioni di contatto. Valore predefinito: "Contact".
se questo valore è vuoto, nessuna etichetta di contatto verrà visualizzata nell'area della firma digitale.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Ottiene o imposta l'etichetta delle informazioni di contatto. Valore predefinito: "Contact".
se questo valore è vuoto, nessuna etichetta di contatto verrà visualizzata nell'area della firma digitale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Ottiene o imposta l'etichetta del motivo. Valore predefinito: "Reason".
se questo valore è vuoto, nessuna etichetta di motivo verrà visualizzata nell'area della firma digitale.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Ottiene o imposta l'etichetta del motivo. Valore predefinito: "Reason".
se questo valore è vuoto, nessuna etichetta di motivo verrà visualizzata nell'area della firma digitale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Ottiene o imposta l'etichetta della posizione. Valore predefinito: "Location".
se questo valore è vuoto, nessuna etichetta di posizione verrà visualizzata nell'area della firma digitale.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Ottiene o imposta l'etichetta della posizione. Valore predefinito: "Location".
se questo valore è vuoto, nessuna etichetta di posizione verrà visualizzata nell'area della firma digitale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Ottiene o imposta l'etichetta firmata digitalmente. Valore predefinito: "Digitally signed by".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Ottiene o imposta l'etichetta firmata digitalmente. Valore predefinito: "Digitally signed by".


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Ottiene o imposta l'etichetta della data di firma. Valore predefinito: "Date".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Ottiene o imposta l'etichetta della data di firma. Valore predefinito: "Date".


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Ottieni o imposta il colore di sfondo dell'aspetto della firma.
Per impostazione predefinita il valore è SystemColors.Windows


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Ottieni o imposta il colore di sfondo dell'aspetto della firma.
Per impostazione predefinita il valore è SystemColors.Windows


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Ottieni o imposta il colore di sfondo dell'aspetto della firma.
Per impostazione predefinita il valore è SystemColors.Windows


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Ottiene o imposta il nome della famiglia di caratteri per visualizzare le etichette. Valore predefinito è "Arial".


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Ottiene o imposta il nome della famiglia di caratteri per visualizzare le etichette. Valore predefinito è "Arial".


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Ottiene o imposta la dimensione del carattere per visualizzare le etichette. Valore predefinito è 10.


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Ottiene o imposta la dimensione del carattere per visualizzare le etichette. Valore predefinito è 10.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


Ottieni o imposta il colore del testo in primo piano dell'aspetto della firma.
Per impostazione predefinita il valore è Color.FromArgb(76, 100, 255)


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Ottieni o imposta il colore del testo in primo piano dell'aspetto della firma.
Per impostazione predefinita il valore è Color.FromArgb(76, 100, 255)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Ottieni o imposta il colore del testo in primo piano dell'aspetto della firma.
Per impostazione predefinita il valore è Color.FromArgb(76, 100, 255)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

