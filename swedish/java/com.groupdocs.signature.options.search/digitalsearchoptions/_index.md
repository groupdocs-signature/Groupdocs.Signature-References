---
title: "DigitalSearchOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar grundalternativ för sökning av digitala signaturer"
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

Representerar grundalternativ för sökning av digitala signaturer

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | Initierar en ny instans av klassen DigitalSearchOptions med standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getComments()](#getComments--) | Kommentarer för Digital-signatur att söka. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Kommentarer för Digital-signatur att söka. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Datum- och tidsintervall för Digital-signatur att söka. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Datum- och tidsintervall för Digital-signatur att söka. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Datum- och tidsintervall för Digital Signature att söka. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Datum- och tidsintervall för Digital Signature att söka. |
|
|  | [getSubjectName()](#getSubjectName--) | För icke tomma värden anger det distinkta ämnesnamnet för certifikatet att söka. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | För icke tomma värden anger det distinkta ämnesnamnet för certifikatet att söka. |
|
|  | [getIssuerName()](#getIssuerName--) | För icke tomma värden anger det distinkta namnet på certifikatutfärdaren att söka. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | För icke tomma värden anger det distinkta namnet på certifikatutfärdaren att söka. |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Initierar en ny instans av klassen DigitalSearchOptions med standardvärden.


### getComments() {#getComments--}
```
public final String getComments()
```


Kommentarer för Digital-signatur att söka.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Kommentarer för Digital-signatur att söka.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Datum- och tidsintervall för Digital-signatur att söka. Nullbart värde kommer att ignoreras.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Datum- och tidsintervall för Digital-signatur att söka. Nullbart värde kommer att ignoreras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Datum- och tidsintervall för Digital Signature att söka. Nullbart värde kommer att ignoreras.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Datum- och tidsintervall för Digital Signature att söka. Nullbart värde kommer att ignoreras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


För icke tomma värden anger det distinkta ämnesnamnet för certifikatet att söka.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


För icke tomma värden anger det distinkta ämnesnamnet för certifikatet att söka.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


För icke tomma värden anger det distinkta namnet på certifikatutfärdaren att söka.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


För icke tomma värden anger det distinkta namnet på certifikatutfärdaren att söka.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

