---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Optionen zum Verifizieren der Text‑Signatur eines Dokuments."
type: docs
weight: 14
url: /de/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Enthält Optionen zum Verifizieren der Text‑Signatur eines Dokuments.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | Initialisiert eine neue Instanz von TextVerifyOptions mit Standardwerten. |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Initialisiert eine neue Instanz von TextVerifyOptions mit Verifizierungstext. |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Initialisiert eine neue Instanz von TextVerifyOptions mit der zu verifizierenden Texteigenschaft und Signaturimplementierung. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Geben Sie den Signaturtext an, falls er verifiziert werden soll. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Geben Sie den Signaturtext an, falls er verifiziert werden soll. |
|
|  | [getMatchType()](#getMatchType--) | Liest oder setzt die Verifizierung des Textübereinstimmungstyps. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Liest oder setzt die Verifizierung des Textübereinstimmungstyps. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Typ der zu verifizierenden Signatur. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Typ der zu verifizierenden Signatur. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Liest oder setzt den Titel des Formularfeldes, um es zu verifizieren. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Liest oder setzt den Titel des Formularfeldes, um es zu verifizieren. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Liest oder setzt den Typ des Formularfeldes, um es zu verifizieren. |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Liest oder setzt den Typ des Formularfeldes, um es zu verifizieren. |
|
|  | [getSignatureID()](#getSignatureID--) | Geben Sie eine Textsignatur-ID größer als null an, falls sie verifiziert werden soll. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Geben Sie eine Textsignatur-ID größer als null an, falls sie verifiziert werden soll. |
|
|  | [toString()](#toString--) | Überschreibt die Konvertierung in einen String. |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Initialisiert eine neue Instanz von TextVerifyOptions mit Standardwerten.


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Initialisiert eine neue Instanz von TextVerifyOptions mit Verifizierungstext.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Zu verifizierender Text |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Initialisiert eine neue Instanz von TextVerifyOptions mit der zu verifizierenden Texteigenschaft und Signaturimplementierung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Zu verifizierender Text. |
|
|  | Implementierung | int | Typ der Signaturimplementierung. |
|

### getText() {#getText--}
```
public final String getText()
```


Geben Sie den Signaturtext an, falls er verifiziert werden soll.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Geben Sie den Signaturtext an, falls er verifiziert werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Liest oder setzt die Verifizierung des Textübereinstimmungstyps.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Liest oder setzt die Verifizierung des Textübereinstimmungstyps.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Typ der zu verifizierenden Signatur.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Typ der zu verifizierenden Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Liest oder setzt den Titel des Formularfeldes, um es zu verifizieren.
Wenn diese Eigenschaft gesetzt ist, wird der Text nur in Textformularfeldern gefunden.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Liest oder setzt den Titel des Formularfeldes, um es zu verifizieren.
Wenn diese Eigenschaft gesetzt ist, wird der Text nur in Textformularfeldern gefunden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Liest oder setzt den Typ des Formularfeldes, um es zu verifizieren.
Wenn diese Eigenschaft gesetzt ist, wird der Text nur in Textformularfeldern gefunden.


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Liest oder setzt den Typ des Formularfeldes, um es zu verifizieren.
Wenn diese Eigenschaft gesetzt ist, wird der Text nur in Textformularfeldern gefunden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Geben Sie eine Textsignatur-ID größer als null an, falls sie verifiziert werden soll. Diese Eigenschaft wird nur für PDF-Dokumente unterstützt.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Geben Sie eine Textsignatur-ID größer als null an, falls sie verifiziert werden soll. Diese Eigenschaft wird nur für PDF-Dokumente unterstützt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibt die Konvertierung in einen String.


**Returns:**
java.lang.String -
