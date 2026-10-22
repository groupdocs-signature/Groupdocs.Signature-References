---
title: "DigitalSearchOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt Basisoptionen für die Suche nach digitalen Signaturen dar"
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.signature.options.search/digitalsearchoptions/
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
| [DigitalSearchOptions()](#DigitalSearchOptions--) | Initialisiert eine neue Instanz der Klasse DigitalSearchOptions mit Standardwerten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getComments()](#getComments--) | Kommentare der zu suchenden digitalen Signatur. |
| [setComments(String value)](#setComments-java.lang.String-) | Kommentare der zu suchenden digitalen Signatur. |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Datums- und Zeitbereich der zu suchenden digitalen Signatur. |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Datums- und Zeitbereich der zu suchenden digitalen Signatur. |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | Datums- und Zeitbereich der zu suchenden digitalen Signatur. |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Datums- und Zeitbereich der zu suchenden digitalen Signatur. |
| [getSubjectName()](#getSubjectName--) | Für nicht leere Werte gibt den distinguished subject name des zu suchenden Zertifikats an. |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Für nicht leere Werte gibt den distinguished subject name des zu suchenden Zertifikats an. |
| [getIssuerName()](#getIssuerName--) | Für nicht leere Werte gibt den distinguished name des zu suchenden Zertifikatsausstellers an. |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Für nicht leere Werte gibt den distinguished name des zu suchenden Zertifikatsausstellers an. |
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Initialisiert eine neue Instanz der Klasse DigitalSearchOptions mit Standardwerten.

### getComments() {#getComments--}
```
public final String getComments()
```


Kommentare der zu suchenden digitalen Signatur.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Kommentare der zu suchenden digitalen Signatur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Datums- und Zeitbereich der zu suchenden digitalen Signatur. Nullable-Wert wird ignoriert.

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Datums- und Zeitbereich der zu suchenden digitalen Signatur. Nullable-Wert wird ignoriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Datums- und Zeitbereich der zu suchenden digitalen Signatur. Nullable-Wert wird ignoriert.

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Datums- und Zeitbereich der zu suchenden digitalen Signatur. Nullable-Wert wird ignoriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Für nicht leere Werte gibt den distinguished subject name des zu suchenden Zertifikats an.

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Für nicht leere Werte gibt den distinguished subject name des zu suchenden Zertifikats an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Für nicht leere Werte gibt den distinguished name des zu suchenden Zertifikatsausstellers an.

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Für nicht leere Werte gibt den distinguished name des zu suchenden Zertifikatsausstellers an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

