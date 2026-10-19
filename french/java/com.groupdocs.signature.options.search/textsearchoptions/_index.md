---
title: "TextSearchOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les options de recherche pour les signatures de texte."
type: docs
weight: 18
url: /fr/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

Représente les options de recherche pour les signatures de texte.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | Initialise une nouvelle instance de la classe TextSearchOptions avec les valeurs par défaut. |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | Initialise une nouvelle instance de la classe TextSearchOptions avec une valeur texte. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getText()](#getText--) | Spécifie le texte de la signature à correspondre lors de la recherche. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Spécifie le texte de la signature à correspondre lors de la recherche. |
|
|  | [getMatchType()](#getMatchType--) | Obtient ou définit le type de correspondance du texte pour la recherche. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Obtient ou définit le type de correspondance du texte pour la recherche. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Spécifie l'implémentation de la signature texte à rechercher. |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | Spécifie l'implémentation de la signature texte à rechercher. |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


Initialise une nouvelle instance de la classe TextSearchOptions avec les valeurs par défaut.


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
```


Initialise une nouvelle instance de la classe TextSearchOptions avec une valeur texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Définir le texte de la signature texte. |
|

### getText() {#getText--}
```
public final String getText()
```


Spécifie le texte de la signature à correspondre lors de la recherche.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Spécifie le texte de la signature à correspondre lors de la recherche.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtient ou définit le type de correspondance du texte pour la recherche.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtient ou définit le type de correspondance du texte pour la recherche.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


Spécifie l'implémentation de la signature texte à rechercher.


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


Spécifie l'implémentation de la signature texte à rechercher.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

