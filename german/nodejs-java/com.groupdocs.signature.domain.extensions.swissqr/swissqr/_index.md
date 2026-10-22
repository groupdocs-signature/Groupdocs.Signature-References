---
title: "SwissQR"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Klasse zum Codieren und Dekodieren des im SwissQR-Code eingebetteten Textes."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Klasse zum Codieren und Dekodieren des im SwissQR-Code eingebetteten Textes.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SwissQR()](#SwissQR--) | Erstellt eine Instanz von SwissQR. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAmount()](#getAmount--) | Liest oder setzt den Zahlungsbetrag. |
| [setAmount(double value)](#setAmount-double-) | Liest oder setzt den Zahlungsbetrag. |
| [getCurrency()](#getCurrency--) | Liest oder setzt die Zahlungswährung. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Liest oder setzt die Zahlungswährung. |
| [getAccount()](#getAccount--) | Liest oder setzt die Kontonummer des Gläubigers. |
| [setAccount(String value)](#setAccount-java.lang.String-) | Liest oder setzt die Kontonummer des Gläubigers. |
| [getCreditor()](#getCreditor--) | Liest oder setzt die Adresse des Gläubigers. |
| [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Liest oder setzt die Adresse des Gläubigers. |
| [getReference()](#getReference--) | Liest oder setzt die Zahlungsreferenz des Gläubigers. |
| [setReference(String value)](#setReference-java.lang.String-) | Liest oder setzt die Zahlungsreferenz des Gläubigers. |
| [getDebtor()](#getDebtor--) | Liest oder setzt die Adresse des Schuldners. |
| [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Liest oder setzt die Adresse des Schuldners. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Liest oder setzt die zusätzliche unstrukturierte Nachricht. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Liest oder setzt die zusätzliche unstrukturierte Nachricht. |
| [getBillInformation()](#getBillInformation--) | Liest oder setzt die zusätzlichen strukturierten Rechnungsinformationen. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Liest oder setzt die zusätzlichen strukturierten Rechnungsinformationen. |
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Erstellt eine Instanz von SwissQR.

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Liest oder setzt den Zahlungsbetrag. Gültige Werte liegen zwischen 0,01 und 999.999.999,99.

Wert: Der Zahlungsbetrag.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Liest oder setzt den Zahlungsbetrag. Gültige Werte liegen zwischen 0,01 und 999.999.999,99.

Wert: Der Zahlungsbetrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Liest oder setzt die Zahlungswährung. Gültige Werte sind "CHF" und "EUR".

Wert: Die Zahlungswährung.

**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Liest oder setzt die Zahlungswährung. Gültige Werte sind "CHF" und "EUR".

Wert: Die Zahlungswährung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Liest oder setzt die Kontonummer des Gläubigers. Kontonummern müssen gültige IBANs einer Bank der Schweiz oder Liechtensteins sein. Leerzeichen sind in der Kontonummer erlaubt.

Wert: Die Kontonummer des Gläubigers.

**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Liest oder setzt die Kontonummer des Gläubigers. Kontonummern müssen gültige IBANs einer Bank der Schweiz oder Liechtensteins sein. Leerzeichen sind in der Kontonummer erlaubt.

Wert: Die Kontonummer des Gläubigers.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Liest oder setzt die Adresse des Gläubigers.

Wert: Die Adresse des Gläubigers.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Liest oder setzt die Adresse des Gläubigers.

Wert: Die Adresse des Gläubigers.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Liest oder setzt die Zahlungsreferenz des Gläubigers. Die Referenz ist für SwissQR-IBANs obligatorisch, d.h. für IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx. Ist sie angegeben, muss die Referenz entweder eine gültige SwissQR-Referenz (entsprechend dem ISR-Referenzformat) oder eine gültige Gläubigerreferenz gemäß ISO 11649 ("RFxxxx") sein. Beide dürfen zur Formatierung Leerzeichen enthalten.

Wert: Die Zahlungsreferenz des Gläubigers.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Liest oder setzt die Zahlungsreferenz des Gläubigers. Die Referenz ist für SwissQR-IBANs obligatorisch, d.h. für IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx. Ist sie angegeben, muss die Referenz entweder eine gültige SwissQR-Referenz (entsprechend dem ISR-Referenzformat) oder eine gültige Gläubigerreferenz gemäß ISO 11649 ("RFxxxx") sein. Beide dürfen zur Formatierung Leerzeichen enthalten.

Wert: Die Zahlungsreferenz des Gläubigers.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Liest oder setzt die Schuldneradresse. Der Schuldner ist optional. Wenn er weggelassen wird, ist sowohl das Setzen dieses Feldes auf null als auch das Setzen einer Adresse mit allen null- oder leeren Werten in Ordnung.

Wert: Die Schuldneradresse.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Liest oder setzt die Schuldneradresse. Der Schuldner ist optional. Wenn er weggelassen wird, ist sowohl das Setzen dieses Feldes auf null als auch das Setzen einer Adresse mit allen null- oder leeren Werten in Ordnung.

Wert: Die Schuldneradresse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Liest oder setzt die zusätzliche unstrukturierte Nachricht.

Wert: Die unstrukturierte Nachricht.

**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Liest oder setzt die zusätzliche unstrukturierte Nachricht.

Wert: Die unstrukturierte Nachricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Liest oder setzt die zusätzlichen strukturierten Rechnungsinformationen.

Wert: Die strukturierte Rechnungsinformation.

**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Liest oder setzt die zusätzlichen strukturierten Rechnungsinformationen.

Wert: Die strukturierte Rechnungsinformation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

