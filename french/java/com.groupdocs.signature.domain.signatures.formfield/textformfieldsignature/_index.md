---
title: "TextFormFieldSignature"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Contient les propriétés de signature du champ de formulaire d'entrée texte pour le document PDF"
type: docs
weight: 15
url: /fr/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Contient les propriétés de signature du champ de formulaire d'entrée texte pour le document PDF

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Crée PdfTextFormFieldSignature avec un nom prédéfini. |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Crée PdfTextFormFieldSignature avec un nom prédéfini. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getText()](#getText--) | Obtient ou définit le texte de la zone de saisie du champ de formulaire. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte de la zone de saisie du champ de formulaire. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Remplace la méthode Equals pour comparer les propriétés de la signature |
|
|  | [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clone l'instance de FormField Signature. |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Crée PdfTextFormFieldSignature avec un nom prédéfini.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Nom de l'objet du champ de formulaire. |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Crée PdfTextFormFieldSignature avec un nom prédéfini.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Nom de l'objet du champ de formulaire. |
|
|  | texte | java.lang.String | Texte de l'objet champ de formulaire. |
|

### getText() {#getText--}
```
public final String getText()
```


Obtient ou définit le texte de la zone de saisie du champ de formulaire.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Obtient ou définit le texte de la zone de saisie du champ de formulaire.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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

