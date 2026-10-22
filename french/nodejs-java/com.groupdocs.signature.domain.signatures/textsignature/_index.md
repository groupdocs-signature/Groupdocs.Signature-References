---
title: "TextSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés de la signature texte."
type: docs
weight: 18
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Contient les propriétés de la signature texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Initialiser l'objet TextSignature avec l'identifiant de signature obtenu après le processus de recherche. |
| [TextSignature()](#TextSignature--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) | Spécifie le texte dans la signature. |
| [setText(String value)](#setText-java.lang.String-) | Spécifie le texte dans la signature. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Spécifie l'implémentation de la signature texte. |
| [getNative()](#getNative--) | Spécifie l'attribut natif. |
| [setNative(boolean value)](#setNative-boolean-) | Spécifie l'attribut natif. |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [deepClone()](#deepClone--) | Cloner l'instance Text Signature. |
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Initialiser l'objet TextSignature avec l'identifiant de signature obtenu après le processus de recherche. Cet identifiant unique est utilisé pour trouver des propriétés supplémentaires pour cette signature dans la couche d'information de signature du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signatureId | java.lang.String | Identifiant de signature unique obtenu par la méthode de signature ou de recherche. |

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Spécifie le texte dans la signature.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Spécifie le texte dans la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Spécifie l'implémentation de la signature texte.

**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Spécifie l'attribut natif. Il est vrai si la signature est spécifique au document.

**Returns:**
booléen
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Spécifie l'attribut natif. Il est vrai si la signature est spécifique au document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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


Cloner l'instance Text Signature.

**Returns:**
java.lang.Object - Retourne une instance clonée de Text Signature.
