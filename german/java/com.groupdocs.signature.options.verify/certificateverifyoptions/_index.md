---
title: "CertificateVerifyOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Optionen zum Verifizieren von Zertifikatsdokumenten."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Enthält Optionen zum Verifizieren von Zertifikatsdokumenten.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Initialisiert eine neue Instanz von TextVerifyOptions mit Standardwerten. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Initialisiert eine neue Instanz von CertificateVerifyOptions mit dem zu prüfenden Betreff. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | Geben Sie den Zertifikatsaussteller an, wenn er überprüft werden soll. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | Geben Sie den Zertifikatsaussteller an, wenn er überprüft werden soll. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Geben Sie die Zertifikatsseriennummer an, wenn sie überprüft werden soll. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Geben Sie die Zertifikatsseriennummer an, wenn sie überprüft werden soll. |
|
|  | [getSubject()](#getSubject--) | Geben Sie das Certificate Subject an, wenn es überprüft werden soll. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Geben Sie das Certificate Subject an, wenn es überprüft werden soll. |
|
|  | [getThumbprint()](#getThumbprint--) | Geben Sie den Zertifikats‑Fingerabdruck an, wenn er überprüft werden soll. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Geben Sie den Zertifikats‑Fingerabdruck an, wenn er überprüft werden soll. |
|
|  | [getMatchType()](#getMatchType--) | Liest oder setzt die Verifizierung des Textübereinstimmungstyps. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Liest oder setzt die Verifizierung des Textübereinstimmungstyps. |
|
|  | [getExpired()](#getExpired--) | Gibt an, ob das Zertifikat aufgrund des Validierungsergebnisses abgelaufen ist. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | Gibt an, ob das Zertifikat aufgrund des Validierungsergebnisses abgelaufen ist. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | Abrufen oder Festlegen, ob der Verifizierungsprozess eine X.509‑Kettenvalidierung mit Grundvalidierungsrichtlinie bereitstellen soll. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Abrufen oder Festlegen, ob der Verifizierungsprozess eine X.509‑Kettenvalidierung mit Grundvalidierungsrichtlinie bereitstellen soll. |
|
|  | [toString()](#toString--) | Überschreibt die Konvertierung in einen String. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Initialisiert eine neue Instanz von TextVerifyOptions mit Standardwerten.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Initialisiert eine neue Instanz von CertificateVerifyOptions mit dem zu prüfenden Betreff.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Betreff | java.lang.String | Zu überprüfendes Subject |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Geben Sie den Zertifikatsaussteller an, wenn er überprüft werden soll.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Geben Sie den Zertifikatsaussteller an, wenn er überprüft werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Geben Sie die Zertifikatsseriennummer an, wenn sie überprüft werden soll.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Geben Sie die Zertifikatsseriennummer an, wenn sie überprüft werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Geben Sie das Certificate Subject an, wenn es überprüft werden soll.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Geben Sie das Certificate Subject an, wenn es überprüft werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Geben Sie den Zertifikats‑Fingerabdruck an, wenn er überprüft werden soll.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Geben Sie den Zertifikats‑Fingerabdruck an, wenn er überprüft werden soll.


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

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Gibt an, ob das Zertifikat aufgrund des Validierungsergebnisses abgelaufen ist.
Eigenschaft ist schreibgeschützt.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Gibt an, ob das Zertifikat aufgrund des Validierungsergebnisses abgelaufen ist.
Eigenschaft ist schreibgeschützt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Abrufen oder Festlegen, ob der Verifizierungsprozess eine X.509‑Kettenvalidierung mit Grundvalidierungsrichtlinie bereitstellen soll.
Standardmäßig ist dieser Wert true.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Abrufen oder Festlegen, ob der Verifizierungsprozess eine X.509‑Kettenvalidierung mit Grundvalidierungsrichtlinie bereitstellen soll.
Standardmäßig ist dieser Wert true.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibt die Konvertierung in einen String.


**Returns:**
java.lang.String -
