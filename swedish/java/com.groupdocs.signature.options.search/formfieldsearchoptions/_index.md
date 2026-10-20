---
title: "FormFieldSearchOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar abstrakta sökalternativ för formulärfältsignaturer."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

Representerar abstrakta sökalternativ för formulärfältsignaturer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [FormFieldSearchOptions()](#FormFieldSearchOptions--) | Initierar en ny instans av klassen SearchFormFieldOptions med standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getType()](#getType--) | Anger typen av formulärfältsignatur om den ska sökas. |
|
|  | [setType(Integer value)](#setType-java.lang.Integer-) | Anger typen av formulärfältsignatur om den ska sökas. |
|
|  | [getName()](#getName--) | Anger reguljärt uttrycksmönster för formulärfältsignaturens namn om den ska sökas. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Anger reguljärt uttrycksmönster för formulärfältsignaturens namn om den ska sökas. |
|
|  | [getValue()](#getValue--) | Anger värdet för formulärfältsignatur om den ska sökas. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Anger värdet för formulärfältsignatur om den ska sökas. |
|
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


Initierar en ny instans av klassen SearchFormFieldOptions med standardvärden.


### getType() {#getType--}
```
public final Integer getType()
```


Anger typen av formulärfältsignatur om den ska sökas. Standardvärdet är null.


**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


Anger typen av formulärfältsignatur om den ska sökas. Standardvärdet är null.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


Anger reguljärt uttrycksmönster för formulärfältsignaturens namn om den ska sökas.
Du kan använda den enkelt som "text" eller ett reguljärt uttryck som "abc\\d+". Standardvärdet är en tom sträng.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Anger reguljärt uttrycksmönster för formulärfältsignaturens namn om den ska sökas.
Du kan använda den enkelt som "text" eller ett reguljärt uttryck som "abc\\d+". Standardvärdet är en tom sträng.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Anger värdet för formulärfältsignatur om den ska sökas. Standardvärdet är null.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Anger värdet för formulärfältsignatur om den ska sökas. Standardvärdet är null.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

