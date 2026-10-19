---
title: "PdfDigitalSignatureAppearance"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Beschreibt das Erscheinungsbild digitaler Signaturen in PDF-Dokumenten."
type: docs
weight: 12
url: /de/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Beschreibt das Erscheinungsbild digitaler Signaturen in PDF-Dokumenten.

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Erstellt ein Signatur‑Darstellungsobjekt mit Standardwerten. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | Liest oder setzt das Kontaktinfo‑Label. |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Liest oder setzt das Kontaktinfo‑Label. |
|
|  | [getReasonLabel()](#getReasonLabel--) | Liest oder setzt das Grund‑Label. |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Liest oder setzt das Grund‑Label. |
|
|  | [getLocationLabel()](#getLocationLabel--) | Liest oder setzt das Standort‑Label. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Liest oder setzt das Standort‑Label. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Liest oder setzt das digital signiert‑Label. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Liest oder setzt das digital signiert‑Label. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Liest oder setzt das Datum‑signiert‑Label. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Liest oder setzt das Datum‑signiert‑Label. |
|
|  | [getBackground()](#getBackground--) | Lese oder setze die Hintergrundfarbe der Signaturdarstellung. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | Lese oder setze die Hintergrundfarbe der Signaturdarstellung. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | Lese oder setze die Hintergrundfarbe der Signaturdarstellung. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | Liest oder setzt den Schriftfamiliennamen zur Anzeige der Labels. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Liest oder setzt den Schriftfamiliennamen zur Anzeige der Labels. |
|
|  | [getFontSize()](#getFontSize--) | Liest oder setzt die Schriftgröße zur Anzeige der Labels. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | Liest oder setzt die Schriftgröße zur Anzeige der Labels. |
|
|  | [getForeground()](#getForeground--) | Lese oder setze die Vordergrund‑Textfarbe der Signaturdarstellung. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | Lese oder setze die Vordergrund‑Textfarbe der Signaturdarstellung. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | Lese oder setze die Vordergrund‑Textfarbe der Signaturdarstellung. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Erstellt ein Signatur‑Darstellungsobjekt mit Standardwerten.


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Liest oder setzt das Kontaktinfo‑Label. Standardwert: "Contact".
Wenn dieser Wert leer ist, wird kein Kontakt‑Label im digitalen Signaturbereich angezeigt.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Liest oder setzt das Kontaktinfo‑Label. Standardwert: "Contact".
Wenn dieser Wert leer ist, wird kein Kontakt‑Label im digitalen Signaturbereich angezeigt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Liest oder setzt das Grund‑Label. Standardwert: "Reason".
Wenn dieser Wert leer ist, wird kein Grund‑Label im digitalen Signaturbereich angezeigt.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Liest oder setzt das Grund‑Label. Standardwert: "Reason".
Wenn dieser Wert leer ist, wird kein Grund‑Label im digitalen Signaturbereich angezeigt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Liest oder setzt das Standort‑Label. Standardwert: "Location".
Wenn dieser Wert leer ist, wird kein Standortetikett im digitalen Signaturbereich angezeigt.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Liest oder setzt das Standort‑Label. Standardwert: "Location".
Wenn dieser Wert leer ist, wird kein Standortetikett im digitalen Signaturbereich angezeigt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Liest oder setzt das digitale Signatur-Label. Standardwert: "Digital signiert von".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Liest oder setzt das digitale Signatur-Label. Standardwert: "Digital signiert von".


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Liest oder setzt das Datum‑Signatur‑Label. Standardwert: "Datum".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Liest oder setzt das Datum‑Signatur‑Label. Standardwert: "Datum".


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Lese oder setze die Hintergrundfarbe der Signaturdarstellung.
Standardmäßig ist der Wert SystemColors.Windows


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Lese oder setze die Hintergrundfarbe der Signaturdarstellung.
Standardmäßig ist der Wert SystemColors.Windows


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Lese oder setze die Hintergrundfarbe der Signaturdarstellung.
Standardmäßig ist der Wert SystemColors.Windows


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Liest oder setzt den Schriftfamiliennamen zur Anzeige der Labels. Standardwert ist "Arial".


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Liest oder setzt den Schriftfamiliennamen zur Anzeige der Labels. Standardwert ist "Arial".


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Liest oder setzt die Schriftgröße zur Anzeige der Labels. Standardwert ist 10.


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Liest oder setzt die Schriftgröße zur Anzeige der Labels. Standardwert ist 10.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


Lese oder setze die Vordergrund‑Textfarbe der Signaturdarstellung.
Standardmäßig ist der Wert Color.FromArgb(76, 100, 255)


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Lese oder setze die Vordergrund‑Textfarbe der Signaturdarstellung.
Standardmäßig ist der Wert Color.FromArgb(76, 100, 255)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Lese oder setze die Vordergrund‑Textfarbe der Signaturdarstellung.
Standardmäßig ist der Wert Color.FromArgb(76, 100, 255)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

