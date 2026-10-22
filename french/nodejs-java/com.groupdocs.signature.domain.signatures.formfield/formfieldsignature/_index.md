---
title: "FormFieldSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés de signature du champ de formulaire."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Contient les propriétés de signature du champ de formulaire.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Spécifie le nom unique du champ de formulaire. |
| [setName(String value)](#setName-java.lang.String-) | Spécifie le nom unique du champ de formulaire. |
| [getType()](#getType--) | Spécifie le type du champ de formulaire. |
| [getValue()](#getValue--) | Spécifie l'objet de données du champ de formulaire. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Spécifie l'objet de données du champ de formulaire. |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [deepClone()](#deepClone--) | Clone l'instance de FormField Signature. |
### getName() {#getName--}
```
public final String getName()
```


Spécifie le nom unique du champ de formulaire.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Spécifie le nom unique du champ de formulaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Spécifie le type du champ de formulaire.

**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Spécifie l'objet de données du champ de formulaire.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Spécifie l'objet de données du champ de formulaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

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
