---
title: "TextSearchOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt Suchoptionen für Textsignaturen dar."
type: docs
weight: 18
url: /de/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

Stellt Suchoptionen für Textsignaturen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | Initialisiert eine neue Instanz der Klasse TextSearchOptions mit Standardwerten. |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | Initialisiert eine neue Instanz der Klasse TextSearchOptions mit einem Textwert. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Gibt den Signaturtext an, der bei der Suche übereinstimmen soll. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Gibt den Signaturtext an, der bei der Suche übereinstimmen soll. |
|
|  | [getMatchType()](#getMatchType--) | Liest oder setzt den Suchtyp für Textübereinstimmungen. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Liest oder setzt den Suchtyp für Textübereinstimmungen. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Gibt die Implementierung der Textsignatur an, nach der gesucht werden soll. |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | Gibt die Implementierung der Textsignatur an, nach der gesucht werden soll. |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


Initialisiert eine neue Instanz der Klasse TextSearchOptions mit Standardwerten.


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
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


Gibt den Signaturtext an, der bei der Suche übereinstimmen soll.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gibt den Signaturtext an, der bei der Suche übereinstimmen soll.


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

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


Gibt die Implementierung der Textsignatur an, nach der gesucht werden soll.


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


Gibt die Implementierung der Textsignatur an, nach der gesucht werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

