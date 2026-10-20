---
title: "TextSearchOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar sökalternativ för textsignaturer."
type: docs
weight: 18
url: /sv/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

Representerar sökalternativ för textsignaturer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | Initierar en ny instans av klassen TextSearchOptions med standardvärden. |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | Initierar en ny instans av klassen TextSearchOptions med textvärde. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getText()](#getText--) | Anger signaturtext som ska matchas vid sökning. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Anger signaturtext som ska matchas vid sökning. |
|
|  | [getMatchType()](#getMatchType--) | Hämtar eller anger söktyp för textmatchning. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Hämtar eller anger söktyp för textmatchning. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Anger implementeringen av textsignatur att söka efter. |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | Anger implementeringen av textsignatur att söka efter. |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


Initierar en ny instans av klassen TextSearchOptions med standardvärden.


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
```


Initierar en ny instans av klassen TextSearchOptions med textvärde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Ange text för textsignaturen. |
|

### getText() {#getText--}
```
public final String getText()
```


Anger signaturtext som ska matchas vid sökning.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Anger signaturtext som ska matchas vid sökning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Hämtar eller anger söktyp för textmatchning.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Hämtar eller anger söktyp för textmatchning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


Anger implementeringen av textsignatur att söka efter.


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


Anger implementeringen av textsignatur att söka efter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

