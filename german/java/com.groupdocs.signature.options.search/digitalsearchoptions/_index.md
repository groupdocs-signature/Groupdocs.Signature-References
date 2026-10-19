---
title: "DigitalSearchOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt Basisoptionen für die Suche nach digitalen Signaturen dar"
type: docs
weight: 12
url: /de/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

Stellt Basisoptionen für die Suche nach digitalen Signaturen dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | Initialisiert eine neue Instanz der Klasse DigitalSearchOptions mit Standardwerten. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getComments()](#getComments--) | Kommentare der digitalen Signatur, nach der gesucht werden soll. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Kommentare der digitalen Signatur, nach der gesucht werden soll. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Datums- und Zeitbereich der digitalen Signatur, nach der gesucht werden soll. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Datums- und Zeitbereich der digitalen Signatur, nach der gesucht werden soll. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Datums- und Zeitbereich der digitalen Signatur, nach der gesucht werden soll. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Datums- und Zeitbereich der digitalen Signatur, nach der gesucht werden soll. |
|
|  | [getSubjectName()](#getSubjectName--) | Gibt für nicht leere Werte den unterscheidbaren Betreffnamen des Zertifikats an, nach dem gesucht werden soll. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Gibt für nicht leere Werte den unterscheidbaren Betreffnamen des Zertifikats an, nach dem gesucht werden soll. |
|
|  | [getIssuerName()](#getIssuerName--) | Gibt für nicht leere Werte den unterscheidbaren Namen des Zertifikatausstellers an, nach dem gesucht werden soll. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Gibt für nicht leere Werte den unterscheidbaren Namen des Zertifikatausstellers an, nach dem gesucht werden soll. |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Initialisiert eine neue Instanz der Klasse DigitalSearchOptions mit Standardwerten.


### getComments() {#getComments--}
```
public final String getComments()
```


Kommentare der digitalen Signatur, nach der gesucht werden soll.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Kommentare der digitalen Signatur, nach der gesucht werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Datums- und Zeitbereich der digitalen Signatur, nach der gesucht werden soll. Nullable Werte werden ignoriert.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Datums- und Zeitbereich der digitalen Signatur, nach der gesucht werden soll. Nullable Werte werden ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Datums- und Zeitbereich der digitalen Signatur, nach der gesucht werden soll. Nullable Werte werden ignoriert.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Datums- und Zeitbereich der digitalen Signatur, nach der gesucht werden soll. Nullable Werte werden ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Gibt für nicht leere Werte den unterscheidbaren Betreffnamen des Zertifikats an, nach dem gesucht werden soll.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Gibt für nicht leere Werte den unterscheidbaren Betreffnamen des Zertifikats an, nach dem gesucht werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Gibt für nicht leere Werte den unterscheidbaren Namen des Zertifikatausstellers an, nach dem gesucht werden soll.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Gibt für nicht leere Werte den unterscheidbaren Namen des Zertifikatausstellers an, nach dem gesucht werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

