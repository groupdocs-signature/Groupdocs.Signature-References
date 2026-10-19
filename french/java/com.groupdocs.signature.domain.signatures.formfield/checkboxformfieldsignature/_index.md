---
title: "CheckboxFormFieldSignature"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Contient les propriétés de signature du champ de formulaire d'entrée case à cocher."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Contient les propriétés de signature du champ de formulaire d'entrée case à cocher.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Crée PdfCheckboxFormFieldSignature avec un nom prédéfini. |
|
|  | [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Crée PdfCheckboxFormFieldSignature avec un nom et une valeur prédéfinis |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getChecked()](#getChecked--) | Obtient ou définit la valeur cochée du champ de formulaire de case à cocher. |
|
|  | [setChecked(boolean value)](#setChecked-boolean-) | Obtient ou définit la valeur cochée du champ de formulaire de case à cocher. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Remplace la méthode Equals pour comparer les propriétés de la signature |
|
|  | [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clone l'instance de FormField Signature. |
|
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Crée PdfCheckboxFormFieldSignature avec un nom prédéfini.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Nom de l'objet du champ de formulaire. |
|

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Crée PdfCheckboxFormFieldSignature avec un nom et une valeur prédéfinis


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Nom de l'objet du champ de formulaire. |
|
|  | isChecked | boolean | Valeur si la case à cocher est cochée |
|

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Obtient ou définit la valeur cochée du champ de formulaire de case à cocher.


**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Obtient ou définit la valeur cochée du champ de formulaire de case à cocher.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

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

