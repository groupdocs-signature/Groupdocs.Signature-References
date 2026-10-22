---
title: "PdfDigitalSignatureAppearance"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Beschreibt das Aussehen digitaler Signaturen in PDF-Dokumenten."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Beschreibt das Aussehen digitaler Signaturen in PDF-Dokumenten.

--------------------

**Learn more**

 *  See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures][]
 *  See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties][]


[Advanced signing document with Digital electronic signatures]: https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/
[Advanced electronic signatures properties]: https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Erstellt ein Signatur‑Darstellungsobjekt mit Standardwerten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContactInfoLabel()](#getContactInfoLabel--) | Liest oder setzt das Kontakt‑Info‑Label. |
| [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Liest oder setzt das Kontakt‑Info‑Label. |
| [getReasonLabel()](#getReasonLabel--) | Liest oder setzt das Grund‑Label. |
| [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Liest oder setzt das Grund‑Label. |
| [getLocationLabel()](#getLocationLabel--) | Liest oder setzt das Standort‑Label. |
| [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Liest oder setzt das Standort‑Label. |
| [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Liest oder setzt das digital signiert‑Label. |
| [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Liest oder setzt das digital signiert‑Label. |
| [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Liest oder setzt das Datum‑Label. |
| [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Liest oder setzt das Datum‑Label. |
| [getBackground()](#getBackground--) | Liest oder setzt die Hintergrundfarbe der Signatur‑Darstellung. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | Liest oder setzt die Hintergrundfarbe der Signatur‑Darstellung. |
| [setBackground(String value)](#setBackground-java.lang.String-) | Liest oder setzt die Hintergrundfarbe der Signatur‑Darstellung. |
| [getFontFamilyName()](#getFontFamilyName--) | Liest oder setzt den Schriftfamiliennamen zur Anzeige der Labels. |
| [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Liest oder setzt den Schriftfamiliennamen zur Anzeige der Labels. |
| [getFontSize()](#getFontSize--) | Liest oder setzt die Schriftgröße zur Anzeige der Labels. |
| [setFontSize(double value)](#setFontSize-double-) | Liest oder setzt die Schriftgröße zur Anzeige der Labels. |
| [getForeground()](#getForeground--) | Liest oder setzt die Vordergrund‑Textfarbe der Signatur‑Darstellung. |
| [setForeground(Color value)](#setForeground-java.awt.Color-) | Liest oder setzt die Vordergrund‑Textfarbe der Signatur‑Darstellung. |
| [setForeground(String value)](#setForeground-java.lang.String-) | Liest oder setzt die Vordergrund‑Textfarbe der Signatur‑Darstellung. |
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Erstellt ein Signatur‑Darstellungsobjekt mit Standardwerten.

### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Liest oder setzt das Kontakt‑Info‑Label. Standardwert: "Contact". Wenn dieser Wert leer ist, wird kein Kontakt‑Label im digitalen Signaturbereich angezeigt.

**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Liest oder setzt das Kontakt‑Info‑Label. Standardwert: "Contact". Wenn dieser Wert leer ist, wird kein Kontakt‑Label im digitalen Signaturbereich angezeigt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Liest oder setzt das Grund‑Label. Standardwert: "Reason". Wenn dieser Wert leer ist, wird kein Grund‑Label im digitalen Signaturbereich angezeigt.

**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Liest oder setzt das Grund‑Label. Standardwert: "Reason". Wenn dieser Wert leer ist, wird kein Grund‑Label im digitalen Signaturbereich angezeigt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Liest oder setzt das Standort‑Label. Standardwert: "Location". Wenn dieser Wert leer ist, wird kein Standort‑Label im digitalen Signaturbereich angezeigt.

**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Liest oder setzt das Standort‑Label. Standardwert: "Location". Wenn dieser Wert leer ist, wird kein Standort‑Label im digitalen Signaturbereich angezeigt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Liest oder setzt das digital signiert‑Label. Standardwert: "Digitally signed by".

**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Liest oder setzt das digital signiert‑Label. Standardwert: "Digitally signed by".

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Liest oder setzt das Datum‑Label. Standardwert: "Date".

**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Liest oder setzt das Datum‑Label. Standardwert: "Date".

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Liest oder setzt die Hintergrundfarbe der Signatur‑Darstellung. Standardmäßig ist der Wert SystemColors.Windows.

**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Liest oder setzt die Hintergrundfarbe der Signatur‑Darstellung. Standardmäßig ist der Wert SystemColors.Windows.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Liest oder setzt die Hintergrundfarbe der Signatur‑Darstellung. Standardmäßig ist der Wert SystemColors.Windows.

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


Liest oder setzt die Vordergrund‑Textfarbe der Signatur‑Darstellung. Standardmäßig ist der Wert Color.FromArgb(76, 100, 255).

**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Liest oder setzt die Vordergrund‑Textfarbe der Signatur‑Darstellung. Standardmäßig ist der Wert Color.FromArgb(76, 100, 255).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Liest oder setzt die Vordergrund‑Textfarbe der Signatur‑Darstellung. Standardmäßig ist der Wert Color.FromArgb(76, 100, 255).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

