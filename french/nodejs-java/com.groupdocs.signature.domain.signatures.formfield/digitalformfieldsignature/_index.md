---
title: "DigitalFormFieldSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés du champ de formulaire d'entrée de signature numérique pour les documents PDF."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

Contient les propriétés du champ de formulaire d'entrée de signature numérique pour les documents PDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | Crée PdfDigitalFormFieldSignature avec un nom prédéfini. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSigned()](#getSigned--) | Propriété en lecture seule qui indique si la signature du champ de formulaire a été signée avec un certificat numérique. |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [deepClone()](#deepClone--) | Clone l'instance de FormField Signature. |
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


Crée PdfDigitalFormFieldSignature avec un nom prédéfini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de l'objet champ de formulaire. |

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


Propriété en lecture seule qui indique si la signature du champ de formulaire a été signée avec un certificat numérique.

**Returns:**
booléen
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
