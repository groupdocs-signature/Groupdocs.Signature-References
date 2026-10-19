---
title: "CertificateSearchOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt Suchoptionen für Zertifikats-Metadaten-Signaturen dar."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.options.search/certificatesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class CertificateSearchOptions extends SearchOptions
```

Stellt Suchoptionen für Zertifikats-Metadaten-Signaturen dar.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [CertificateSearchOptions()](#CertificateSearchOptions--) | Initialisiert eine neue Instanz der Klasse TextSearchOptions mit Standardwerten. |
|
|  | [CertificateSearchOptions(String text)](#CertificateSearchOptions-java.lang.String-) | Initialisiert eine neue Instanz der Klasse TextSearchOptions mit einem Textwert. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Gibt den Zertifikats‑Eigenschaftstext an, der bei der Suche abgeglichen werden soll. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Gibt den Zertifikats‑Eigenschaftstext an, der bei der Suche abgeglichen werden soll. |
|
|  | [getMatchType()](#getMatchType--) | Liest oder setzt den Suchtyp für Textübereinstimmungen. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Liest oder setzt den Suchtyp für Textübereinstimmungen. |
|
### CertificateSearchOptions() {#CertificateSearchOptions--}
```
public CertificateSearchOptions()
```


Initialisiert eine neue Instanz der Klasse TextSearchOptions mit Standardwerten.


### CertificateSearchOptions(String text) {#CertificateSearchOptions-java.lang.String-}
```
public CertificateSearchOptions(String text)
```


Initialisiert eine neue Instanz der Klasse TextSearchOptions mit einem Textwert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Setzt den Text der Textsignatur. |
|

### getText() {#getText--}
```
public final String getText()
```


Gibt den Zertifikats‑Eigenschaftstext an, der bei der Suche abgeglichen werden soll.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gibt den Zertifikats‑Eigenschaftstext an, der bei der Suche abgeglichen werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Liest oder setzt den Suchtyp für Textübereinstimmungen.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Liest oder setzt den Suchtyp für Textübereinstimmungen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

