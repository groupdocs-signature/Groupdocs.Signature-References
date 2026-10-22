---
title: "RadioButtonFormFieldSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés de signature du champ de formulaire d'entrée bouton radio."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

Contient les propriétés de signature du champ de formulaire d'entrée bouton radio.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | Crée RadioButtonFieldSignature avec un nom prédéfini. |
| [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Crée RadioButtonFieldSignature avec un nom prédéfini et une liste d'éléments. |
| [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Crée RadioButtonFieldSignature avec un nom prédéfini, une liste d'éléments et une valeur sélectionnée. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSelected()](#getSelected--) | Contient la valeur sélectionnée. |
| [setSelected(String value)](#setSelected-java.lang.String-) | Contient la valeur sélectionnée. |
| [getItems()](#getItems--) | Obtient ou définit la liste d'options des boutons radio. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Obtient ou définit la liste d'options des boutons radio. |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [deepClone()](#deepClone--) | Clone l'instance de FormField Signature. |
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


Crée RadioButtonFieldSignature avec un nom prédéfini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de l'objet champ de formulaire. |

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


Crée RadioButtonFieldSignature avec un nom prédéfini et une liste d'éléments.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de l'objet champ de formulaire. |
| éléments | java.util.List<java.lang.String> | Valeurs de la liste des boutons radio. |

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


Crée RadioButtonFieldSignature avec un nom prédéfini, une liste d'éléments et une valeur sélectionnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de l'objet champ de formulaire. |
| éléments | java.util.List<java.lang.String> | Valeurs de la liste des boutons radio. |
| sélectionné | java.lang.Object | Valeur sélectionnée. |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Contient la valeur sélectionnée.

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Contient la valeur sélectionnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Obtient ou définit la liste d'options des boutons radio.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Obtient ou définit la liste d'options des boutons radio.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<java.lang.String> |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Écrase la méthode Equals pour comparer les propriétés de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Objet de signature à comparer. |

**Returns:**
boolean - Retourne true si l'objet signature passé a le même type et que toutes ses propriétés sont égales aux propriétés de cette instance.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Remplace la méthode GetHashCode

**Returns:**
int - Code de hachage de la signature
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone l'instance de FormField Signature.

**Returns:**
java.lang.Object - Retourne une instance de FormField Signature clonée.
