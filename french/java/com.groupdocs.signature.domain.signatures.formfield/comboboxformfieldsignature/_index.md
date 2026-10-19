---
title: "ComboboxFormFieldSignature"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Contient les propriétés de signature du champ de formulaire d'entrée liste déroulante."
type: docs
weight: 11
url: /fr/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Contient les propriétés de signature du champ de formulaire d'entrée liste déroulante.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Crée ComboboxFormFieldSignature avec un nom prédéfini. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Crée ComboboxFormFieldSignature avec un nom prédéfini et une liste d'options. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Crée ComboboxFormFieldSignature avec un nom prédéfini, une liste d'options et une valeur sélectionnée. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSelected()](#getSelected--) | Obtient ou définit la valeur sélectionnée. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Obtient ou définit la valeur sélectionnée. |
|
|  | [getItems()](#getItems--) | Obtient ou définit la liste d'options du combo-box. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Obtient ou définit la liste d'options du combo-box. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Remplace la méthode Equals pour comparer les propriétés de la signature |
|
|  | [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clone l'instance de FormField Signature. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Crée ComboboxFormFieldSignature avec un nom prédéfini.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Nom de l'objet du champ de formulaire. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Crée ComboboxFormFieldSignature avec un nom prédéfini et une liste d'options.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Nom de l'objet du champ de formulaire. |
|
|  | items | java.util.List<java.lang.String> | Valeurs de la liste du combo-box. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Crée ComboboxFormFieldSignature avec un nom prédéfini, une liste d'options et une valeur sélectionnée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Nom de l'objet du champ de formulaire. |
|
|  | items | java.util.List<java.lang.String> | Valeurs de la liste du combo-box. |
|
|  | selected | java.lang.Object | Valeur sélectionnée. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Obtient ou définit la valeur sélectionnée.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Obtient ou définit la valeur sélectionnée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Obtient ou définit la liste d'options du combo-box.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Obtient ou définit la liste d'options du combo-box.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<java.lang.String> |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Remplace la méthode Equals pour comparer les propriétés de la signature


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | signature | java.lang.Object | Objet de signature à comparer. |
|

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
java.lang.Object - Retourne une instance clonée de FormField Signature.

