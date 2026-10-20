---
title: "PdfDigitalSignatureAppearance"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Beskriver utseendet på digitala signaturer i PDF-dokument."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Beskriver utseendet på digitala signaturer i PDF-dokument.

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Skapar signaturutseendeobjekt med standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | Hämtar eller anger etikett för kontaktinformation. |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Hämtar eller anger etikett för kontaktinformation. |
|
|  | [getReasonLabel()](#getReasonLabel--) | Hämtar eller anger etikett för anledning. |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Hämtar eller anger etikett för anledning. |
|
|  | [getLocationLabel()](#getLocationLabel--) | Hämtar eller anger etikett för plats. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Hämtar eller anger etikett för plats. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Hämtar eller anger etikett för digitalt signerat. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Hämtar eller anger etikett för digitalt signerat. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Hämtar eller anger etikett för signeringsdatum. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Hämtar eller anger etikett för signeringsdatum. |
|
|  | [getBackground()](#getBackground--) | Hämta eller ange bakgrundsfärg för signaturutseende. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | Hämta eller ange bakgrundsfärg för signaturutseende. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | Hämta eller ange bakgrundsfärg för signaturutseende. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | Hämtar eller anger teckensnittsfamiljens namn för att visa etiketterna. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Hämtar eller anger teckensnittsfamiljens namn för att visa etiketterna. |
|
|  | [getFontSize()](#getFontSize--) | Hämtar eller anger teckenstorlek för att visa etiketterna. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | Hämtar eller anger teckenstorlek för att visa etiketterna. |
|
|  | [getForeground()](#getForeground--) | Hämta eller ange förgrundstextfärg för signaturutseende. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | Hämta eller ange förgrundstextfärg för signaturutseende. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | Hämta eller ange förgrundstextfärg för signaturutseende. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Skapar signaturutseendeobjekt med standardvärden.


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Hämtar eller anger etikett för kontaktinformation. Standardvärde: "Contact".
Om detta värde är tomt visas ingen kontaktetikett i det digitala signaturområdet.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Hämtar eller anger etikett för kontaktinformation. Standardvärde: "Contact".
Om detta värde är tomt visas ingen kontaktetikett i det digitala signaturområdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Hämtar eller anger anledningsetikett. Standardvärde: "Reason".
Om detta värde är tomt visas ingen anledningsetikett i det digitala signaturområdet.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Hämtar eller anger anledningsetikett. Standardvärde: "Reason".
Om detta värde är tomt visas ingen anledningsetikett i det digitala signaturområdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Hämtar eller anger platsetikett. Standardvärde: "Location".
Om detta värde är tomt visas ingen platsetikett i det digitala signaturområdet.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Hämtar eller anger platsetikett. Standardvärde: "Location".
Om detta värde är tomt visas ingen platsetikett i det digitala signaturområdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Hämtar eller anger digitalt signerat etikett. Standardvärde: "Digitally signed by".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Hämtar eller anger digitalt signerat etikett. Standardvärde: "Digitally signed by".


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Hämtar eller anger datum signerat etikett. Standardvärde: "Date".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Hämtar eller anger datum signerat etikett. Standardvärde: "Date".


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Hämta eller ange bakgrundsfärg för signaturutseende.
Som standard är värdet SystemColors.Windows


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Hämta eller ange bakgrundsfärg för signaturutseende.
Som standard är värdet SystemColors.Windows


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Hämta eller ange bakgrundsfärg för signaturutseende.
Som standard är värdet SystemColors.Windows


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Hämtar eller anger teckensnittsfamiljens namn för att visa etiketterna. Standardvärde är "Arial".


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Hämtar eller anger teckensnittsfamiljens namn för att visa etiketterna. Standardvärde är "Arial".


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Hämtar eller anger teckenstorlek för att visa etiketterna. Standardvärde är 10.


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Hämtar eller anger teckenstorlek för att visa etiketterna. Standardvärde är 10.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


Hämta eller ange förgrundstextfärg för signaturutseende.
Som standard är värdet Color.FromArgb(76, 100, 255)


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Hämta eller ange förgrundstextfärg för signaturutseende.
Som standard är värdet Color.FromArgb(76, 100, 255)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Hämta eller ange förgrundstextfärg för signaturutseende.
Som standard är värdet Color.FromArgb(76, 100, 255)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

