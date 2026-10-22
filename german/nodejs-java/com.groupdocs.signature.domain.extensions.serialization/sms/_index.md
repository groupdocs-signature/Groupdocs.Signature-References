---
title: "SMS"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt die Details des SMS‑Kurzmitteilungsdienstes dar."
type: docs
weight: 18
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/sms/
---
**Inheritance:**
java.lang.Object
```
public class SMS
```

Stellt die Details des SMS‑Kurzmitteilungsdienstes dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SMS()](#SMS--) | Erstellt eine VCard‑Instanz mit Standardwerten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNumber()](#getNumber--) | Liest oder setzt die Telefonnummer des SMS‑Empfängers. |
| [setNumber(String value)](#setNumber-java.lang.String-) | Liest oder setzt die Telefonnummer des SMS‑Empfängers. |
| [getMessage()](#getMessage--) | Liest oder setzt den Inhalt der SMS‑Nachricht. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Liest oder setzt den Inhalt der SMS‑Nachricht. |
| [equals(Object obj)](#equals-java.lang.Object-) | Überschreibt die Equals‑Methode, um SMS‑Eigenschaften zu vergleichen. |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
### SMS() {#SMS--}
```
public SMS()
```


Erstellt eine VCard‑Instanz mit Standardwerten.

### getNumber() {#getNumber--}
```
public final String getNumber()
```


Liest oder setzt die Telefonnummer des SMS‑Empfängers.

**Returns:**
java.lang.String
### setNumber(String value) {#setNumber-java.lang.String-}
```
public final void setNumber(String value)
```


Liest oder setzt die Telefonnummer des SMS‑Empfängers.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Liest oder setzt den Inhalt der SMS‑Nachricht.

**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Liest oder setzt den Inhalt der SMS‑Nachricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Überschreibt die Equals‑Methode, um SMS‑Eigenschaften zu vergleichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | SMS‑Objekt zum Vergleichen. |

**Returns:**
bool - Gibt true zurück, wenn das übergebene SMS‑Objekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode

**Returns:**
int - VCard‑Hashcode
