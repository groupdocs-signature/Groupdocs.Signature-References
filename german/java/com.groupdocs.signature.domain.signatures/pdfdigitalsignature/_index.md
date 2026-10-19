---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält PDF-Digital-Signatur-Eigenschaften."
type: docs
weight: 15
url: /de/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Enthält PDF-Digital-Signatur-Eigenschaften.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | Initialisiert Pdf Digital Signature ohne Zertifikat. |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Erstellt Pdf Digital Signature mit angegebenem Zertifikat. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | Vom Unterzeichner bereitgestellte Informationen, um einem Empfänger die Kontaktaufnahme mit dem Unterzeichner zu ermöglichen |
um die Signatur zu überprüfen, z. B.
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Vom Unterzeichner bereitgestellte Informationen, um einem Empfänger die Kontaktaufnahme mit dem Unterzeichner zu ermöglichen |
um die Signatur zu überprüfen, z. B.
|
|  | [getLocation()](#getLocation--) | Der CPU-Hostname oder der physische Standort der Signatur. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Der CPU-Hostname oder der physische Standort der Signatur. |
|
|  | [getReason()](#getReason--) | Der Grund für die Signatur, z. B. (I agree\u0420\u0406\u0420\u201a\u0412¦). |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Der Grund für die Signatur, z. B. (I agree\u0420\u0406\u0420\u201a\u0412¦). |
|
|  | [getType()](#getType--) | Typ der PDF-Digitalunterschrift. |
|
|  | [setType(int value)](#setType-int-) | Typ der PDF-Digitalunterschrift. |
|
|  | [getTimeStamp()](#getTimeStamp--) | Zeitstempel für die PDF-Digitalunterschrift. |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Zeitstempel für die PDF-Digitalunterschrift. |
|
|  | [getShowProperties()](#getShowProperties--) | Erzwinge das Anzeigen/Verbergen von Signatur-Eigenschaften. |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | Erzwinge das Anzeigen/Verbergen von Signatur-Eigenschaften. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
|  | [deepClone()](#deepClone--) | Barcode-Signaturinstanz klonen. |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Initialisiert Pdf Digital Signature ohne Zertifikat.


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Erstellt Pdf Digital Signature mit angegebenem Zertifikat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Zertifikat | java.security.KeyStore | X509-Zertifikat. |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Vom Unterzeichner bereitgestellte Informationen, um einem Empfänger die Kontaktaufnahme mit dem Unterzeichner zu ermöglichen
um die Signatur zu überprüfen, z. B. eine Telefonnummer.


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Vom Unterzeichner bereitgestellte Informationen, um einem Empfänger die Kontaktaufnahme mit dem Unterzeichner zu ermöglichen
um die Signatur zu überprüfen, z. B. eine Telefonnummer.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Der CPU-Hostname oder der physische Standort der Signatur.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Der CPU-Hostname oder der physische Standort der Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Der Grund für die Signatur, z. B. (I agree\u0420\u0406\u0420\u201a\u0412¦).


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Der Grund für die Signatur, z. B. (I agree\u0420\u0406\u0420\u201a\u0412¦).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Typ der PDF-Digitalunterschrift.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Typ der PDF-Digitalunterschrift.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Zeitstempel für die PDF-Digitalunterschrift.
Standardwert ist null.


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Zeitstempel für die PDF-Digitalunterschrift.
Standardwert ist null.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Erzwinge das Anzeigen/Verbergen von Signatur-Eigenschaften. Falls ShowProperties wahr ist, Signatur
Feld hat vordefiniertes Anzeigeformat
Digital signiert von {
KontaktInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Datum: {Date} Grund: {
Grund
(#getReason.getReason/#setReason(String).setReason(String))}
Ort: {
Ort
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties ist standardmäßig wahr.


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Erzwinge das Anzeigen/Verbergen von Signatur-Eigenschaften. Falls ShowProperties wahr ist, Signatur
Feld hat vordefiniertes Anzeigeformat
Digital signiert von {
KontaktInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Datum: {Date} Grund: {
Grund
(#getReason.getReason/#setReason(String).setReason(String))}
Ort: {
Ort
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties ist standardmäßig wahr.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Signatur | java.lang.Object | Signaturobjekt zum Vergleich. |
|

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Signaturobjekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode


**Returns:**
int - Signatur-Hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Barcode-Signaturinstanz klonen.


**Returns:**
java.lang.Object - Gibt eine geklonte Barcode‑Signaturinstanz zurück.

