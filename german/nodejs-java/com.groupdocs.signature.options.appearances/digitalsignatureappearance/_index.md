---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Beschreibt das Aussehen der Signaturzeile für digitale Signaturen."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Beschreibt das Aussehen der Signaturzeile für digitale Signaturen. Eine Signaturzeile kann nur für eine digitale Signatur verwendet werden. Die Signaturzeile befindet sich immer auf der ersten Seite. Diese Funktion kann für die Dateiformate .docx, .doc, .odt und .xlsx nützlich sein.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Erstellt ein Signature Line Appearance-Objekt. |
| [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Erstellt ein Signature Line Appearance mit angegebenen Werten (signer, title, email). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSigner()](#getSigner--) | Liest oder setzt signer-Name für die Signaturzeile. |
| [setSigner(String value)](#setSigner-java.lang.String-) | Liest oder setzt signer-Name für die Signaturzeile. |
| [getTitle()](#getTitle--) | Liest oder setzt einen title für die Signaturzeile. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Liest oder setzt einen title für die Signaturzeile. |
| [getEmail()](#getEmail--) | Liest oder setzt eine email, die in der Signaturzeile angezeigt wird. |
| [setEmail(String value)](#setEmail-java.lang.String-) | Liest oder setzt eine email, die in der Signaturzeile angezeigt wird. |
| [toString()](#toString--) | Überschreibe die String-Konvertierung. |
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Erstellt ein Signature Line Appearance-Objekt.

### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Erstellt ein Signature Line Appearance mit angegebenen Werten (signer, title, email).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signer | java.lang.String | Unterzeichnername. |
| Titel | java.lang.String | Signaturtitel. |
| E-Mail | java.lang.String | E-Mail des Autors. |

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Liest oder setzt signer-Name für die Signaturzeile.

**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Liest oder setzt signer-Name für die Signaturzeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Liest oder setzt einen title für die Signaturzeile.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Liest oder setzt einen title für die Signaturzeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Liest oder setzt eine email, die in der Signaturzeile angezeigt wird.

**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Liest oder setzt eine email, die in der Signaturzeile angezeigt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.

**Returns:**
java.lang.String -
