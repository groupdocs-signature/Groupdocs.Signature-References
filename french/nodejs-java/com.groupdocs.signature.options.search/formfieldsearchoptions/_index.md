---
title: "FormFieldSearchOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options de recherche abstraites pour les signatures de champs de formulaire."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

Représente les options de recherche abstraites pour les signatures de champs de formulaire.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FormFieldSearchOptions()](#FormFieldSearchOptions--) | Initialise une nouvelle instance de la classe SearchFormFieldOptions avec les valeurs par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Spécifie le type de signature de champ de formulaire s'il doit être recherché. |
| [setType(Integer value)](#setType-java.lang.Integer-) | Spécifie le type de signature de champ de formulaire s'il doit être recherché. |
| [getName()](#getName--) | Spécifie le motif d'expression régulière du nom de la signature de champ de formulaire s'il doit être recherché. |
| [setName(String value)](#setName-java.lang.String-) | Spécifie le motif d'expression régulière du nom de la signature de champ de formulaire s'il doit être recherché. |
| [getValue()](#getValue--) | Spécifie la valeur de la signature de champ de formulaire s'il doit être recherché. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Spécifie la valeur de la signature de champ de formulaire s'il doit être recherché. |
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


Initialise une nouvelle instance de la classe SearchFormFieldOptions avec les valeurs par défaut.

### getType() {#getType--}
```
public final Integer getType()
```


Spécifie le type de signature de champ de formulaire s'il doit être recherché. La valeur par défaut est null.

**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


Spécifie le type de signature de champ de formulaire s'il doit être recherché. La valeur par défaut est null.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


Spécifie le motif d'expression régulière du nom de la signature de champ de formulaire s'il doit être recherché. Vous pouvez l'utiliser simplement comme "text" ou une expression régulière comme "abc\\d+". La valeur par défaut est une chaîne vide.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Spécifie le motif d'expression régulière du nom de la signature de champ de formulaire s'il doit être recherché. Vous pouvez l'utiliser simplement comme "text" ou une expression régulière comme "abc\\d+". La valeur par défaut est une chaîne vide.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Spécifie la valeur de la signature de champ de formulaire s'il doit être recherché. La valeur par défaut est null.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Spécifie la valeur de la signature de champ de formulaire s'il doit être recherché. La valeur par défaut est null.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

