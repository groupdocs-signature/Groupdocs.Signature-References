---
title: "EPC"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt den Quick Response Code des European Payments Council dar."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

Stellt den Quick Response Code des European Payments Council dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EPC()](#EPC--) | Instanziiert ein neues EPC‑Objekt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Liest oder setzt den Namen des Begünstigten. |
| [setName(String value)](#setName-java.lang.String-) | Liest oder setzt den Namen des Begünstigten. |
| [getBIC()](#getBIC--) | Liest oder setzt den BIC des Begünstigten mit einer Länge von bis zu 11 Zeichen. |
| [setBIC(String value)](#setBIC-java.lang.String-) | Liest oder setzt den BIC des Begünstigten mit einer Länge von bis zu 11 Zeichen. |
| [getIBAN()](#getIBAN--) | Liest oder setzt das Konto des Begünstigten (IBAN). |
| [setIBAN(String value)](#setIBAN-java.lang.String-) | Liest oder setzt das Konto des Begünstigten (IBAN). |
| [getAmount()](#getAmount--) | Liest oder setzt den Betrag. |
| [setAmount(double value)](#setAmount-double-) | Liest oder setzt den Betrag. |
| [getCode()](#getCode--) | Liest oder setzt den Geschäftscode mit bis zu 4 Zeichen. |
| [setCode(String value)](#setCode-java.lang.String-) | Liest oder setzt den Geschäftscode mit bis zu 4 Zeichen. |
| [getReference()](#getReference--) | Liest oder setzt die Zahlungsreferenz (maximal 35 Zeichen). |
| [setReference(String value)](#setReference-java.lang.String-) | Liest oder setzt die Zahlungsreferenz (maximal 35 Zeichen). |
| [getRemittance()](#getRemittance--) | Liest oder setzt die Verwendungsinformation (maximal 140 Zeichen). |
| [setRemittance(String value)](#setRemittance-java.lang.String-) | Liest oder setzt die Verwendungsinformation (maximal 140 Zeichen). |
| [getInformation()](#getInformation--) | Liest oder setzt Hinweisinformationen. |
| [setInformation(String value)](#setInformation-java.lang.String-) | Liest oder setzt Hinweisinformationen. |
| [getVersion()](#getVersion--) | Implementierung der EPC / SEPA QR‑Code‑Version. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Implementierung der EPC / SEPA QR‑Code‑Version. |
| [getCharset()](#getCharset--) | Implementierung des EPC / SEPA QR‑Code‑Zeichensatzes. |
| [setCharset(String value)](#setCharset-java.lang.String-) | Implementierung des EPC / SEPA QR‑Code‑Zeichensatzes. |
| [getIdentification()](#getIdentification--) | Identifikation des EPC / SEPA QR‑Codes. |
| [setIdentification(String value)](#setIdentification-java.lang.String-) | Identifikation des EPC / SEPA QR‑Codes. |
| [equals(Object source)](#equals-java.lang.Object-) | Überschreibt die Equals‑Methode, um EPC‑Eigenschaften zu vergleichen. |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
### EPC() {#EPC--}
```
public EPC()
```


Instanziiert ein neues EPC‑Objekt.

### getName() {#getName--}
```
public final String getName()
```


Liest oder setzt den Namen des Begünstigten. Maximale Länge beträgt 70 Zeichen.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Liest oder setzt den Namen des Begünstigten. Maximale Länge beträgt 70 Zeichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


Liest oder setzt den BIC des Begünstigten mit einer Länge von bis zu 11 Zeichen.

**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


Liest oder setzt den BIC des Begünstigten mit einer Länge von bis zu 11 Zeichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


Liest oder setzt das Konto des Begünstigten (IBAN). Die IBAN besteht aus bis zu 34 alphanumerischen Zeichen.

**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


Liest oder setzt das Konto des Begünstigten (IBAN). Die IBAN besteht aus bis zu 34 alphanumerischen Zeichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Liest oder setzt den Betrag.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Liest oder setzt den Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


Liest oder setzt den Geschäftscode mit bis zu 4 Zeichen.

**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


Liest oder setzt den Geschäftscode mit bis zu 4 Zeichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Liest oder setzt die Zahlungsreferenz (maximal 35 Zeichen). Dieses Feld und das Feld für Verwendungsinformation schließen sich gegenseitig aus.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Liest oder setzt die Zahlungsreferenz (maximal 35 Zeichen). Dieses Feld und das Feld für Verwendungsinformation schließen sich gegenseitig aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


Liest oder setzt die Verwendungsinformation (maximal 140 Zeichen). Dieses Feld und das Feld für Zahlungsreferenz schließen sich gegenseitig aus.

**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


Liest oder setzt die Verwendungsinformation (maximal 140 Zeichen). Dieses Feld und das Feld für Zahlungsreferenz schließen sich gegenseitig aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


Liest oder setzt Hinweis-Informationen. Maximal 70 Zeichen.

**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


Liest oder setzt Hinweis-Informationen. Maximal 70 Zeichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


EPC / SEPA QR-Code Versionsimplementierung. Standardmäßig ist dieser Wert auf 002 gesetzt.

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


EPC / SEPA QR-Code Versionsimplementierung. Standardmäßig ist dieser Wert auf 002 gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


EPC / SEPA QR-Code Zeichensatzimplementierung. Standardmäßig ist dieser Wert auf 1 gesetzt.

**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


EPC / SEPA QR-Code Zeichensatzimplementierung. Standardmäßig ist dieser Wert auf 1 gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


EPC / SEPA QR-Code Identifikation. Standardmäßig ist dieser Wert auf SCT gesetzt.

**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


EPC / SEPA QR-Code Identifikation. Standardmäßig ist dieser Wert auf SCT gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Überschreibt die Equals‑Methode, um EPC‑Eigenschaften zu vergleichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Quelle | java.lang.Object | EPC-Objekt zum Vergleich. |

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Adressobjekt denselben Typ hat und alle seine Eigenschaften mit den Eigenschaften dieser Instanz übereinstimmen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode

**Returns:**
int - E-Mail-Hashcode
