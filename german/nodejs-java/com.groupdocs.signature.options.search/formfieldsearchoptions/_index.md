---
title: "FormFieldSearchOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt abstrakte Suchoptionen für Formularfeld‑Signaturen dar."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

Stellt abstrakte Suchoptionen für Formularfeld‑Signaturen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FormFieldSearchOptions()](#FormFieldSearchOptions--) | Initialisiert eine neue Instanz der Klasse SearchFormFieldOptions mit Standardwerten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt den Typ der Formularfeld‑Signatur an, wenn sie gesucht werden soll. |
| [setType(Integer value)](#setType-java.lang.Integer-) | Gibt den Typ der Formularfeld‑Signatur an, wenn sie gesucht werden soll. |
| [getName()](#getName--) | Gibt das reguläre Ausdrucksmuster des Namens der Formularfeld‑Signatur an, wenn es gesucht werden soll. |
| [setName(String value)](#setName-java.lang.String-) | Gibt das reguläre Ausdrucksmuster des Namens der Formularfeld‑Signatur an, wenn es gesucht werden soll. |
| [getValue()](#getValue--) | Gibt den Wert der Formularfeld‑Signatur an, wenn sie gesucht werden soll. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gibt den Wert der Formularfeld‑Signatur an, wenn sie gesucht werden soll. |
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


Initialisiert eine neue Instanz der Klasse SearchFormFieldOptions mit Standardwerten.

### getType() {#getType--}
```
public final Integer getType()
```


Gibt den Typ der Formularfeld‑Signatur an, wenn sie gesucht werden soll. Der Standardwert ist null.

**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


Gibt den Typ der Formularfeld‑Signatur an, wenn sie gesucht werden soll. Der Standardwert ist null.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


Gibt das reguläre Ausdrucksmuster des Namens der Formularfeld‑Signatur an, wenn es gesucht werden soll. Sie können es einfach als "text" oder als regulären Ausdruck wie "abc\\d+" verwenden. Der Standardwert ist ein leerer String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gibt das reguläre Ausdrucksmuster des Namens der Formularfeld‑Signatur an, wenn es gesucht werden soll. Sie können es einfach als "text" oder als regulären Ausdruck wie "abc\\d+" verwenden. Der Standardwert ist ein leerer String.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Gibt den Wert der Formularfeld‑Signatur an, wenn sie gesucht werden soll. Der Standardwert ist null.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Gibt den Wert der Formularfeld‑Signatur an, wenn sie gesucht werden soll. Der Standardwert ist null.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

